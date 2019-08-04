# [Java Recommendation Web Project](http://35.175.228.215/jupiter/)

This full stack project was deployed to AWS EC2 and runs on Tomcat 9.0. Users can register, login and see nearby events based on their location. They can then favorite events and get personalized recommendation. The event data are gathered from the Ticketmaster API.

## Front End

The front end is implemented by html, css and javascript. Ajax is used to connect to endpoints to fetch item data and login/logout.

## Back End

The backend runs on Tomcat. Different endpoints serve as RESTful APIs to handle functionalities such as searching items, recommendation, and database application. 

## Database

MySQL and MongoDB are implemented as the databases. The default is MySQL. If the data gets larger, some ETL work has to be done to migrate the data to MongoDB.
