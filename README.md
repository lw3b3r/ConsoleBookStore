# CF Books Store Console App

## Project Description

This application is designed with functionality that would make virtual shopping much simpler! Customers can sign up for an account, place orders, view their order history, and specific location inventory. It also comes with an additional interface for managing your business. Managers can view and replenish location inventory, add new products, and view the order history of specific locations. This application used Entity Framework Core to connect to a PostgreSQL database, and C# to create the front end.

## Technologies Used

- C# Programming
- ADO.NET Entity Framework Core
- Testing Process / SDLC
- Defect Logging
- PostgreSQL
- XML

## Features

- Users can sign up for accounts or log in to existing accounts
- Users can view products and inventory per location
- User can place orders for multiple products at a time and view order history
- Manager users can view location order history
- Manager users can replenish inventory at locations
- Manager users can add new products to inventories
- Order histories are able to be sorted by Date and by Price, both ascending and descending

To-do list:

- Add product details page to display book details, full synopsis, as well as reviews

## Getting Started

To Clone:
`git clone https://github.com/201019-UiPath/WeberLindsey-Project1.git`

- Once cloned, you will need to create an appsettings.json file to direct the application to your database
- Database tables can be created using EF Core Code-First approach using these commands:
- `dotnet ef migrations add initial -c StoreContext --startup-project ../StoreUI/StoreUI.csproj`
- `dotnet ef database update --startup-project ../StoreUI/StoreUI.csproj `
- You will also need to populate your database with seed data of your choice

## Usage

After installation is complete and database migrated:

> Use command `dotnet run --project Store.sln` to run the CF Books Store Console App.
> From here, you will be able to create a user account or sign in to one.
> Once signed in, you will be provided navigational prompts to be able to view inventory, place orders, view order history and change store locations.

## License

This project uses the following license: [MIT License](https://github.com/201019-UiPath/WeberLindsey-Project1/blob/main/LICENSE).
