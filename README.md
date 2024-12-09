# KOPIBARA ☕

KOPIBARA is a modern web-based coffee ordering system built with ASP.NET Core 8.0. It provides a seamless experience for customers to browse and order various coffee beverages, with both hot and iced options available.

<p align="center">
  <img src="Kopibara/wwwroot/images/KOPIBARA.png" alt="KOPIBARA Logo" width="300"/>
</p>

## Features

- 🔐 **Secure Authentication**
  - Google OAuth integration for user authentication
  - Custom admin authentication system
  - Secure cookie-based session management

- ☕ **Comprehensive Beverage Menu**
  - Wide variety of coffee options
  - Hot and iced variations available
  - Including popular drinks like:
    - Espresso
    - Cappuccino
    - Latte
    - Macchiato
    - Mocha
    - Vietnamese Coffee
    - Irish Coffee
    - Black Coffee

- 💻 **Modern Web Interface**
  - Responsive design
  - User-friendly navigation
  - Beautiful product imagery

## Technology Stack

- **Framework**: ASP.NET Core 8.0
- **Database**: Microsoft SQL Server with Entity Framework Core
- **Authentication**: Google OAuth 2.0
- **Frontend**: ASP.NET MVC with Razor Views
- **Additional Libraries**:
  - RestSharp
  - Newtonsoft.Json

## Prerequisites

- .NET 8.0 SDK
- Microsoft SQL Server
- Visual Studio 2022 (recommended) or VS Code
- Google OAuth credentials (for authentication features)

## Installation

1. Clone the repository
```bash
git clone https://github.com/Khadalicioso/kopibara.git
```

2. Navigate to the project directory
```bash
cd Kopibara
```

3. Restore dependencies
```bash
dotnet restore
```

4. Update the connection string in `appsettings.json` to point to your SQL Server instance

5. Apply database migrations
```bash
dotnet ef database update
```

6. Configure Google OAuth
   - Add your Google OAuth credentials in `appsettings.json`:
   ```json
   {
     "GoogleKeys": {
       "ClientId": "your-client-id",
       "ClientSecret": "your-client-secret"
     }
   }
   ```

7. Run the application
```bash
dotnet run
```

## Configuration

The application uses various configuration settings in `appsettings.json`:

- Database connection string
- Google OAuth credentials
- Session configuration
- Authentication settings

## Project Structure

- 📁 **Controllers/**: MVC Controllers handling request logic
- 📁 **Models/**: Data models and view models
- 📁 **Views/**: Razor views for the user interface
- 📁 **Data/**: Database context and migrations
- 📁 **wwwroot/**: Static files (images, CSS, JavaScript)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Copyright 2024 KPL Team. All rights reserved.

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Coffee icons and images used in the project
- ASP.NET Core community
- All contributors who have helped shape this project

---

Made with ❤️ by KPL Team
