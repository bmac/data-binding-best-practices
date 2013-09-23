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

What is data binding?
- Libs: ko, angular, ember, ractive, meteor
- MVC, MVVM, MVP
- Model
- View
- ViewModel/Controller/$scope
- why is 
- don't put logic im templates (ember does it right)
- Templates providing arguments to functions is useful.
  - ko makes it hard (anomous functions in templates)
  - angular makes it easy
  - ember make it easy (and impossible to do wrong)

I love data binding

Critiques of data binding
- look like onclick handlers
  - http://egghead.io/lessons/angularjs-an-alternative-approach-to-controllers
