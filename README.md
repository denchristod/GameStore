# GameStore API

GameStore API is a RESTful backend built using **ASP.NET Core Minimal APIs** and **Entity Framework Core**.  
It provides endpoints for managing a collection of games, including creating, retrieving, updating, and deleting records.

The application is fully self-contained and uses **SQLite**, automatically creating and seeding the database on startup.

---

## Features

- CRUD operations for games
- RESTful API design
- Entity Framework Core with SQLite
- Automatic database creation and migrations
- Asynchronous database operations
- DTO-based data shaping
- Relationship handling (Games ↔ Genres)
- Clean and minimal API structure
- Automatic data seeding (preloaded genres)

---

## Tech Stack

- ASP.NET Core (Minimal APIs)
- Entity Framework Core
- SQLite
- C#

---

## API Endpoints

### Games

| Method | Endpoint        | Description          |
|--------|----------------|----------------------|
| GET    | /games         | Get all games        |
| GET    | /games/{id}    | Get game by ID       |
| POST   | /games         | Create a new game    |
| PUT    | /games/{id}    | Update a game        |
| DELETE | /games/{id}    | Delete a game        |

---

## Future Implementations
React-based frontend to consume the API and provide a full-stack user experience.

---

## Getting Started

### Prerequisites

- .NET SDK installed

### Run the project

```bash
dotnet run
