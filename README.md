This is a basic ASP.NET website project centered around cars and ordering functionality, it has CRUD(Create, Read, Update, Delete) functionality and database integration using Entity Framework, It allows the creation of orders by the user with the button "Create New Order" which stores the information and displays is in the orders tab after it has been finalized.

You can run the project by clicking the "Run with Visual Studio" option from the green “Code” button. It will ask you to choose a location to clone the repository to, and then you can start running it.

The project uses SQL Server LocalDB. The connection string is in appsettings.json, make sure to update it if you want to use a different location.
If using SQL login, replace "Trusted_Connection=True" with User Id=USERNAME;Password=PASSWORD;

  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\MSSQLLocalDB;Database=CarsWebDb;Trusted_Connection=True;MultipleActiveResultSets=true"
