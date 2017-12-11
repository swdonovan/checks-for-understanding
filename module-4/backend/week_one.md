## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
  Object Oriented JS
  
2. What are some tools to help debug JavaScript code?
 PryJS, Debugger, Console, Node, node debug
 
3. What are some tools you need in order to unit test your JavaScript?

 Chai and Mocha
 
4. What is the syntax for invoking a function?
  Function name and parens

5. What's `this` in JavaScript?
  The abstract objects 'self'/attributes of object
  
6. What is Webpack and why is it useful?
  Pre compiles and mini-fys our JS files into one file
  
7. When/why do you want to use event delegation?
  Event delegation is useful for client tracking, UX/UI, If you don't want to refresh a page, if you want to load a page with certain portions of the page loading before the others, etc.
  
8. What's `npm` and what do we use it for?
Node Package Manager.  It manages the library and extensions we need for JS 

#### Review  
9. What's the MVC design pattern? Describe each part of MVC.
  Models Views Controllers. Framework where the request response cycle by definition starts after client request in the Models talking to DB then rendering the views before the controller tells where to load.  should be CMVC
  
10. What are a few ways to optimize a Rails application?
  Caching certain sets of data or DB loads.  Breaking the rails application into a API endpoint/s and using any other language that can use multiple processes. Using background workers to handle jobs that clients don't need to wait on.
  
11. What's a background worker? When would we want to use a background worker?
  Does a prescribed job in the background, away from the client/user in an attempt to make the load faster or the experience better essentially.
