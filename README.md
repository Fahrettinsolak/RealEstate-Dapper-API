# RealEstate-Dapper-API

This project is the API part of a property management system developed using **ASP.NET** and **Dapper**. The project is designed to manage property data and perform various CRUD (Create, Read, Update, Delete) operations.

## Project Summary

### Features
- **Property Records**: You can add new property records, update or delete existing records.
- **Dapper ORM Usage**: Dapper is used for fast and efficient data access.
- **CRUD Operations**: Provides full CRUD operations on property data.
- **Fast Query**: You can make faster and more flexible queries by writing SQL queries directly.

## Installation and Operation

### Requirements
- Visual Studio 2019 or later
- .NET Core 3.1 or later
- MSSQL Server

### Installation Steps
1. Download the project files to your computer.
2. Open the project with Visual Studio.

3. Edit your database connection string in the `appsettings.json` file.

4. Create the necessary database on MSSQL Server.

5. Run the project and test it in your development environment.

### Go Live
1. Install the required .NET runtime version on the server.

2. Import your database to the server.

3. Upload the project files to the server and update your connection string in the `appsettings.json` file.

4. Publish your application and go live with your API.

## Project Structure

- **Controllers**: Layer where API endpoints are defined.
- **Repositories**: Layer where data access and Dapper queries are written.
- **Models**: Model classes where real estate and other related entities are defined.
- **Services**: Service classes where business logic is written.

## Topics to Learn

When you complete this project, you will have knowledge of the following topics:
- ASP.NET Core API Development
- Using Dapper ORM
- Accessing Data with SQL Queries
- Layered Architecture Structure
- CRUD Operations and Data Management
- Configuration with `appsettings.json` File
- Dependency Injection (DI)
- Performance Data Access

## Technologies Used
- ASP.NET Core
- Dapper ORM
- MSSQL
- SQL
- C#

## Contributors
- **[Fahrettin Solak]** - Project development and management.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact
For any questions or feedback, please contact me at [fahsolak@gmail.com](mailto:fahsolak@gmail.com).

---

Good luck in developing your project and bringing it live!
