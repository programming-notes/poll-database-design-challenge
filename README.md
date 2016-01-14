# Design a Poll Database Schema 
 
##Summary 

 As we all saw in the last election, the polling has become integral to politics and many other field.  Polls are only useful if you can quickly and accurately access the data.  There are many ways to form a polling database, but let's start by building a basic system with users, questions, responses and votes. 

Here are the requirements of our system: 

1. A user can create many polls, but a poll is created by only one user
2. A poll has a question, e.g., "Who do you support for President in 2016?"
3. A poll has many responses, e.g., "Hillary Clinton", "Arnold Schwarzenegger", etc.
4. A user can vote in any poll, but only once, and they can only select one response per poll

##Releases

###Release 0 : Design schema

Design a database schema for a polling app that meets the requirements.
 

Use [SQL Designer][] to create your schema.  When you are done, save the XML of your schema and copy it to the source file `poll_schema.md`. Then, take a screenshot of your final schema design, and upload it using a free image-upload service like [Min.us](http://minus.com).  Paste the URL of the screenshot into your file (before your XML code). 

<!-- ##Optimize Your Learning  -->


[SQL Designer]: https://schemadesigner.devbootcamp.com/
