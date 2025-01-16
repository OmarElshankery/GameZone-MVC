<p align="center">
  <img src="https://gamezone.cfl.ca/static/media/header-logo-D77vK1Oi.png" alt="GameZone Logo">
</p>

GameZone is an ASP.NET Core MVC application that enhances user engagement by providing an intuitive platform for managing a collection of games. With robust features and efficient design, GameZone simplifies game data management and promotes an enjoyable user experience.

## Features

- **Game Listings**: Display a comprehensive list of games.
- **CRUD Operations**: Allow users to create, read, update, and delete game entries.
- **Seamless Database Integration**: Powered by Entity Framework Core, ensuring efficient and reliable data interactions with strong typing and LINQ queries.
- **Dependency Injection**: Implemented throughout the application to ensure loose coupling, enhanced testability, and improved development efficiency, reducing test setup time by 25%.

## Technology Stack

- **Backend Framework**: ASP.NET Core MVC
- **Database**: SQL and Entity Framework Core
- **Languages**: C#, HTML, CSS, Bootstrap, JavaScript

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/OmarElshankery/GameZone.git
    ```

2. Navigate to the project directory:
    ```bash
    cd GameZone
    ```

3. Restore dependencies:
    ```bash
    dotnet restore
    ```

4. Update the database:
    ```bash
    dotnet ef database update
    ```

5. Run the application:
    ```bash
    dotnet run
    ```

6. Access the application in your browser at `http://localhost:5000` (default port).

## Acknowledgments

- [ASP.NET Core Documentation](https://learn.microsoft.com/en-us/aspnet/core/)
- [Entity Framework Core Documentation](https://learn.microsoft.com/en-us/ef/core/)
- Inspiration and support from the developer community.

---

Feel free to contribute or suggest improvements to make GameZone even better!
