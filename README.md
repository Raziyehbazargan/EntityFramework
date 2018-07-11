# EntityFramework
a small project that shows both Database-First workflow and Code-First workflow


## Code First Approach

It is very popular approach between MVC programmers. It has full control over the code rather than database activity. Using this approach we can do all the database activity from the code. So, we can say manual changes to database have been lost to use this and everything is depended on the code.


## Database First Approach

If you have already a designed database and you don’t want to do extra effort then you can go with this approach. If your database is ready then Entity Framework will complete his duty and create entities for you.

You can modify the database manually and update model from database. So, we can say, entity framework is able to create your model classes based on tables and columns from relational database.

- Create your databse in SQl Server
- In Visual Studio / Project , right click on the project and add `ADo.Net Entity Data Model` , select `EF designer from db` and create connection string


###### reference: `https://www.c-sharpcorner.com/blogs/code-first-vs-database-first-vs-model-first-approach1`
