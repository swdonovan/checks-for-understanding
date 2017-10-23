## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?
  Node by definition is a Server Side Enviroment for JavaScript, written in vanilla JS.  I commonly mistake it for a server side language similar to Ruby but that would be incorrect as it just transforms a client-side based language into a server-side capable language?

2. What is Express? What is Express similar to in the Ruby world?
  Express is a JS loosely-structred, unopinionated(supposedly) framework responsible for handling the incoming HTTP request and responses coming from clients and/or servers.  Express in Ruby terms would be tightly associated with Sinatra due to its high maluability for different aspects
  
  
3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.
  after installing and require/loading the express app into our JS server File to handle the incoming HTTP req/responses we use expresses built in 'get', 'post', 'patch', 'put', 'delete' and other various methods to handle the request and then handle the outgoing response. 
  
  app.get('/', function(request, response) {
  response.sendFile(path.join(__dirname+'/welcome.html'))
})

4. What do we use Knex for?
  Knex is our Object Relational Map tool similar to Active Record for database queries.  Very raw methods to query DB's without the raw SQL strings alone but with SQL understanding, inputing raw sql is relatively as easy or easier than AR.

5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?
  Node-Server;  Using JS/Node/Express Routing prototype.  Breaking a whole load of logic out of the server.  Lighten the Server to minimalistic amounts, in attempts to abstract and hide as much of the logic that was being used.  Its ugly but has/had a plan
  
6. How do you execute raw SQL in node?
  DB-Variable-assigned-to-the-DB.raw('input your sql string') 
  
7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?
  Advantages:  In this case here the endpoints for the old and repos for the new are left untouched due to different languages allowing the switching/version control application should the new endpoints not work out.  Abstracts out a lot of different logic inadvertently by the need to query the DB. Dual cache abilities of the different languages.
  
  Disadvantages:  One client side hosting site needed along with another hosting site for the Server.  Maintainance. A lot of re-used code if working with JS languages.

#### Review  

8. Describe DNS.
  The internets directory of all where to find IP's based on a directory or registry of Domain Names allowing client requests to be routed to the correct IP addressed Servers.
  
9. What does writing clean code mean to you?
  Highly re-used/usable, Understandable, concise blocks of executable code where it should take at max 2-3 simultaneous file views and 3-5 different file grabs to understand data and objects being passed along with the path being walked when executing the block of Code.
  
  As this an ever shifting opinion amongst myself and others with vast more experience, I quantify clean/not going to worry about it for weeks "code" simply if myself or anyone is able to look at a snippet of code through short quick msgs and be able to fully discuss what is happening with out the need to pretense as the code as repeatedly been used to such extent that it is intuitively understood. Dreams
  
10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?
  Tables:  
    -Guests
    -Reservations
    -Rooms
    -Users (multiple roles)
