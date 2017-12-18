## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?
  Javascript enviroment for running server side logic that can interact with multiple different databases
  
2. What is Express? What is Express similar to in the Ruby world?
  Javascript Framework.  Express is similar to Sinatra.
  
3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.
  set up the server.js file to listen on a certain port and direct all routes through the HTTP verb protocols.
  
4. What do we use Knex for?
  Interacting with Postgres Databases
  
5. How **could** you organize your code to follow the MVC design pattern in your Quantified Self project?
  lib/models/pojos etc etc etc
6. How do you execute raw SQL in node?
  depends on the orm that you are using
    knex.raw if it is knex
    
7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?
  Allows for one application to be maintained with out the possibility of bothering the other set of code.
    Disadvantages: Maintaining two seperate applications could costly and time consuming.  Testing against changes to one application affecting the other adds to the cost:time:maintainability factor.
    

#### Review  

8. Describe DNS.
  Domain Named System
    Centralized directory for the entire internet.  
      
9. What does writing clean code mean to you?
  Easy to read and re-use.  Easy to read explain or reacclimate at any point in the future
  
10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality? Hint: think about what tables you would need in the database, how those records would relate to each other, and good OOP.

  Reservations
    Booking a user into a room
    Reservation belongs to a room and to a user
  
  Users
    confirmed authenticated user and have higher privelages that a guest who can still make a reservation
  
  Guests
    Non authenticated users but still allowed to make a reservation
  
  Managers
    Authenticated user only allowed to do CRUD fucntionality with the reservations
  
  Admin
    Overall application admin
  
  Rooms
    Record keeping whether room is available or not on certain dates
