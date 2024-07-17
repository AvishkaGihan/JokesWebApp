# JokesWebApp

JokesWebApp is a web application built using ASP.NET Core that allows users to manage and share jokes.

## Features

- User authentication and authorization using ASP.NET Core Identity
- CRUD operations for jokes
- Responsive design using Bootstrap

## Technologies Used

- ASP.NET Core
- Entity Framework Core
- SQL Server
- jQuery
- Bootstrap

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/JokesWebApp.git
   ```
2. Ensure you have the .NET Core SDK installed.
3. Update the connection string in `appsettings.json` to point to your SQL Server instance.
4. Run the following commands in the project directory:
   ```bash
   dotnet restore
   dotnet ef database update
   dotnet run
   ```
5. Navigate to `https://localhost:5001` in your web browser.

## Project Structure

- `Data/`: Contains database context and migrations
- `Models/`: Contains model classes
- `Controllers/`: Contains controller classes
- `Views/`: Contains Razor views
- `wwwroot/`: Contains static files (CSS, JS, images)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
