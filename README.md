
Bookstore Application working with NoSQL via MongoDB from an Angular Front-end 
with ASP.NET Core backend. This solution helps you to quickly 
get started working with MongoDB database integration in ASP.NET Core, 
all while following the best practices and a Clean Architecture.

# What is MongoDB?

MongoDB is an open-source cross platform document-oriented database. It stores data records in the form of JSON-like structures and is classified as a NoSQL data store. It also supports scalability and replication and is one of the most popular options for NoSQL data store usecases.


# Clean Architecture

1. Layered architecture with seperated UI, Core and Contracts libraries
2. DB Interactions built using Repository pattern and follows all SOLID principles
3. Angular UI which facilitates CRUD operations performed over the database
4. API validates payload using Fluent Validations
5. Docker scripts included making the solution container deployment ready
6. One command setup using Docker-Compose, file included

# Technologies

* [ASP.NET Core (.NET 6)](https://docs.microsoft.com/en-us/aspnet/core/introduction-to-aspnet-core?view=aspnetcore-6.0)
* [Angular](https://angular.io/)
* [Mongo DB](https://www.mongodb.com/)
* [Fluent Validation](https://fluentvalidation.net/)
* [Docker](https://www.docker.com/)


# How to get started

1. Install the latest .NET 6 SDK
2. Install the latest Node.js LTS
3. Navigate to ./MongoBookStoreApp.Web/ClientApp and run npm install
4. Navigate to ./MongoBookStoreApp.Web/ClientApp and run npm start to launch the front end (Angular)
5. Navigate to ./MongoBookStoreApp.Web/ and run dotnet run to launch the back end (ASP.NET Core Web API)

# Docker Deployment

To run the application through docker, pull the solution into your local directory and run the below command in your Terminal / Command-Line (requires a working Docker installation and Docker running)

> docker-compose up --force-recreate --build

Once the container is up, visit http://localhost:5000 in your local browser. 



