data-binding-best-practices
===========================
Who?
- Brendan McLoughlin
- Boston MA
- Bocoup
- Open Web Developer. What does that mean?
- NetChef Enterprize inventory tracking tool for resturants
- EMWeb
- Store Manager for ruelala
- aircheck
- open source work for knockout, ember, angular-ui?

Where did this talk come from?
- When I started workong on the store manager project I discovered at a highlevel it was very similar to netchef
  - data binding framework
  - lots and lots of tables (for tabular data)
  - REST API on the back end. (working with json, get, put, post and such)
- I started noticeing silimaraties between ko and angular in what do do right and worng

I love data binding
- I think you should use it
- Admittedly not for everything
- Great for applications that have complex UI requirements
  - forms, validation (enterprize apps)
  - managing both touch and pointer based interactions
  - WebRTC
  - UIs that have to respond to realtime data changes
  - Any sort of complext dom manipulation in response to data

- What is data binding?
  - Data binding is the process that establishes a connection between the application UI and business logic.
  - when the data changes its value, the elements that are bound to the data reflect changes automatically.
  - Simple example
- Data bindings is not a new concept
  - WPF
  - flex
  - apple uses the term key value observation
  - others
- Popularular JavaScript data binding libraries
  - Knockout (July 5, 2010)
  - Angular (late 2009)
  - Ember (2011)
    - Sproutcore (2007)
  - Meteor (2011)
  - Ractive (Jul 31, 2012)
  - Others
- MVC, MVVM, MVP
- Model
  - Persisted state
- View
  - The DOM
- ViewModel/Controller/$scope 
  - A place to store not persisted state 
  - computed state
  - Usually works with the model
  - Yehuda Katz calls this a Presentation Model
- why is 
- don't put logic im templates (ember does it right)
- Templates providing arguments to functions is useful.
  - ko makes it hard (anomous functions in templates)
  - angular makes it easy
  - ember make it easy (and impossible to do wrong)


Backbone does all that!
- backbone does provide good patterns and observing hooks
- too much logic happens in views (update both models and dom)
- backbone encourage smaller, more templates

Presentation

Critiques of data binding
- look like onclick handlers
  - http://egghead.io/lessons/angularjs-an-alternative-approach-to-controllers
