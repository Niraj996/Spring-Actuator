Problem 
You Create a Spring project and start creating class, mapping restpoints, adding dep etc
but.....
How can i monitor and manage whats happing in my application?
How can i check the application health?
How can i access application metrics?

Solution 
   Just expose ur end points and u can monitor and manage ur application
   easily gets DevOps functionality out-of-thebox
   Simply add the dependency to ur POM file
   REST endpoints are automatically added to ur application

By defult only /help is exposed but it can be customsed as per required on /info
 Now we can expose all the endpoints with wildCards '*'
Can also expose individual endpoints with a comma-delimited list
/threaddump List all the threads running in ur application and useful for analyzing and profiling ur apps performance
/mapping list all req mapping , useful for finding out what request mapping are available


Here everything happes in application.properties file so just check that 
