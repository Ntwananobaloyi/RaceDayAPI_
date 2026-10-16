[![.NET Build](https://github.com/Ntwananobaloyi/practise_Git/actions/workflows/dotnet.yml/badge.svg)](https://github.com/Ntwananobaloyi/practise_Git/actions/workflows/dotnet.yml)
# RaceDayAPI
A RESTful API built with C#, ASP.NET Core and Entity Framework Core for managing race day information. The API is documented with Swagger, covered by automated unit tests, and built and tested on every push using GitHub Actions.

Table of Contents
Features
Tech Stack
Getting Started
Running the API
API Documentation (Swagger)
API Endpoints
Running the Tests
Continuous Integration
Project Structure
Author

Features
Full CRUD (Create, Read, Update, Delete) operations through RESTful endpoints
Data stored with Entity Framework Core
Interactive API documentation with Swagger UI
Unit tests written with xUnit
Automated build and test pipeline with GitHub Actions

Running the API

From Visual Studio: set the API project as the startup project and press F5 (or Ctrl+F5 to run without debugging).

From the command line:

bash
dotnet run --project RaceDayAPI

The API will start on the URLs shown in the console (for example https://localhost:7000).

API Documentation (Swagger)

With the API running, open Swagger UI in your browser:

https://localhost:<port>/swagger

From there you can view every endpoint, see the request and response models, and try the endpoints out directly.

API Endpoints

Update this table so it matches the controllers in your project.

Method	Endpoint	Description
GET	/api/races	Get all races
GET	/api/races/{id}	Get a single race by ID
POST	/api/races	Create a new race
PUT	/api/races/{id}	Update an existing race
DELETE	/api/races/{id}	Delete a race
