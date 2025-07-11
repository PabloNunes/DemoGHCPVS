# DemoGHCP

A Blazor Server application built with .NET 9.

## Description

This is a demo Blazor Server application that includes:
- Home page with welcome message
- Weather forecast page with sample data
- Counter page (interactive component)
- Bootstrap UI styling

## Features

- **Blazor Server**: Interactive web UI using C# instead of JavaScript
- **Bootstrap**: Modern responsive design
- **Weather Component**: Demonstrates async data loading and streaming rendering
- **Counter Component**: Shows interactive client-side functionality
- **.NET 9**: Built on the latest .NET framework

## Getting Started

### Prerequisites

- .NET 9 SDK
- Visual Studio 2022 or VS Code

### Running the Application

1. Clone the repository
2. Navigate to the project directory
3. Run the application:
   ```bash
   dotnet run
   ```
4. Open your browser to `https://localhost:5001` (or the URL shown in the terminal)

## Project Structure

```
DemoGHCP/
??? Components/
?   ??? Layout/
?   ?   ??? MainLayout.razor
?   ?   ??? NavMenu.razor
?   ??? Pages/
?   ?   ??? Counter.razor
?   ?   ??? Error.razor
?   ?   ??? Home.razor
?   ?   ??? Weather.razor
?   ??? App.razor
?   ??? Routes.razor
?   ??? _Imports.razor
??? Properties/
?   ??? launchSettings.json
??? wwwroot/
?   ??? app.css
?   ??? favicon.png
?   ??? lib/
??? Program.cs
??? DemoGHCP.csproj
```

## Technologies Used

- .NET 9
- Blazor Server
- Bootstrap 5
- ASP.NET Core

## License

This project is open source and available under the [MIT License](LICENSE).