# Blazor WebApp Movies

This is a simple Blazor Server web application for managing a movie collection.  
It demonstrates CRUD operations, EF Core integration with SQLite, and the use of [QuickGrid](https://learn.microsoft.com/en-us/aspnet/core/blazor/components/quickgrid) for fast and responsive tabular data display.

## Features

- List all movies in a sortable table
- Create, edit, view, and delete movies
- Filter movies by title via query string
- Uses SQLite as the database backend
- Uses `QuickGrid` for a fast and modern UI
- Built with ASP.NET Core Blazor Server

## Tech Stack

- **Blazor Server (.NET 8)**  
- **Entity Framework Core**
- **SQLite**
- **QuickGrid**  
- **ASP.NET Core Dependency Injection**

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- IDE like Visual Studio, Rider, or VS Code

### Clone and Run

```bash
git clone https://github.com/thornicek/Blazor-WebApp-Movies.git
cd Blazor-WebApp-Movies

dotnet restore
dotnet ef database update
dotnet run