## Week Two - Module 4 Recap



1. What's one difference between ES5 and ES6?
  Syntax in various areas.
  ;'s not required.
  explicit returns not required. 
  
2. What's the difference between asynchronous and synchronous JavaScript? 
  synchronous JavaScript, which is JS's natural behavior, is processing functions or executable code in the specified order and never breaking order.
  aysynchronous JS, which has special requirements with either engines or libraries, which allows it to run is taking applicable code and running multiple functions or modules of code at the same time. 
  
3. What are the four pillars of Object Oriented programming?

  abstraction--> Hiding parts of one module of code from another while still exposing the same code to see what it only needs.
  polymorphism--> Allowing sets of code to work and behave like the parent or base code of them.  SImilar with inheritance
  encapsulation--> Hiding data and inner workings of one set of code from another set of code.
  inheritance--> Allowing different modules of code that have different responsibilites, to act or behave in the same manner and produce the same desired result. 
  
4. What are some tools available in JavaScript to help you write object oriented code?

  class and constructors. 
  mulitple variables
  static functions
  
5. What are some key concepts to be aware of when refactoring your JavaScript?
  four pillars of OOP
  understandable and followable code because JS is hard enough to follow with out confusing it.
  commented out code that is concise explaining functionality sometimes is helpful if not overused
  
6. What's a callback function and what are some reasons when we use/need callback functions?
  is the next set of executable code to be ran in another function.
  
7. What's the scope of variables in Javascript?
  Local and Global--> Due to compilation any variable declared outside of a function or class  will be hoisted(?) when compiled and essentially be globally available while any other variable declared inside functions or classes will only be available locally within that function or class or any other nested functions or classes.
  
8. What's the difference between `==` and `===` in JavaScript?
  == - checks comparison on general attributes or less strictly the  values of two objects 
  === - checks comparison is much more strict where it will check type as well as values
  
9. Why do front end frameworks exist?
  An attempt at organization. Preferences, needs etc

#### Review  

10. Why do people say "HTTP is stateless"?
  Once a webpage loads its natural, unaltered behavior is to close the connection and not change state until and command to request a different state or sets of data is given to refresh.
  
11. Describe a RESTful API.
  sends and recieves json or xml information through the HTTP transfer protocol
  
12. What are some main characteristics of a team following an agile workflow?
  scrum, standups, oop, pivoting
13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?
  advantages--> allows app owner/teams not to have to manage sensitive user data only requesting and storing what is needed.  
  disadvantages--> what happens if OAauth ends up hackable at some point?
