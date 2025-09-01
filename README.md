# BookStoreApi

A sample ASP.NET Core 9 Web API project using MongoDB, based on the Microsoft Learn tutorial.

## Features
- RESTful CRUD API for books
- MongoDB integration with `MongoDB.Driver`
- Swagger UI for testing

## Requirements
- [.NET 9 SDK](https://dotnet.microsoft.com/download)
- [MongoDB](https://www.mongodb.com/try/download/community) running locally or in the cloud

## Getting Started
1. Clone or download this repo.

2. Update `appsettings.json` with your MongoDB connection string:
   ```json
   "BookStoreDatabase": {
     "ConnectionString": "mongodb://localhost:27017",
     "DatabaseName": "BookStore",
     "BooksCollectionName": "Books"
   }
