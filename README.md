# PizzaHub

## Project Description
PizzaHub is a web application that allows a user to order pizza from a selection of stores. The users are able to create and account and login. Account creation has a variety of client-side validation, namely making sure that the user has entered a correct email address format. Once logged in, they are greeted with a homepage showing them all their previous orders. A tab option shown on top allows the user to start another customer order. From there a user is able to select a store, and order specific premade pizzas defined by each store, or make a customer pizza, where each store's sizes/crusts/toppings/prices are all specific to them. Once they place their order, they will be brought back to their home page and a timer will start showing time until delivery.
If a manager logs into the application, they will have an additional tab option on top to manage their store, where they will be able to see all orders to the store, have the ability to update inventory and prices for their store, and add new toppings/sizes/crusts and new premade pizzas to their menus.

## Technologies Used
- Frontend
  - HTML
  - CSS
  - Javascript
- Backend
  - C#
  - .NET 5
  - ASP.NET Core Web API
  - Entity Framework Core - version 5.0.4
  - SQL Server Database

## Features
- User can select a variety of stores
- User can make a custom order for that store
- User can select either a premade pizza or make a custom pizza
- User can see previous order history
- User can see a timer for order delivery
- Store manager can see all orders to their store
- Store manager can update inventory and prices
- Store manager can add new pizza components(sizes/crusts/toppings)
- Store manager can add new prebuilt pizzas
- Client-Side validation

To-do list:
- Better customer feedback as part of the UI
- Server-Side validation
- Sorting order history

## Getting Started
### Frameworks Needed
* [.NET 5](https://dotnet.microsoft.com/download)
* Some SQL Database
### Getting the code and setting up the database
1. Get the code from GitHub (git clone https://github.com/03012021-dotnet-uta/NicholaWong_p1.git)
2. Get EntityFramework Nuget Packages
    - [EntityFramework Core](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/5.0.4)
    - [EntityFramework Tools](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Tools/5.0.4)
    - [EntityFramework Design](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/5.0.4)
    - [EntityFramework SQLServer](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/5.0.4)
3. Open Bash in the root folder and create the database (dotnet-ef database add --project PizzaBox.Repository --context DatabaseCreationContext)
### Starting up the API and the website
1. Open chas in the root folder and start the api (dotnet run --project PizzaBox.ApiExplorer/PizzaBox.ApiExplorer.csproj
2. Go to the localhost stated (default https://localhost:5001)
3. Mess around in the application!

## Usage
Once installed, feel free to create an account and interact with the application. You can login, order a pizza from any of the default stores with whatever premade and/or custom pizzas you want. By default everyone is considered just a normal customer. In order to become a store manager, you will need to manual add yourself or update your account information on the database server end.

