# GameStore API

GameStore API is a RESTful backend built using **ASP.NET Core Minimal APIs** and **Entity Framework Core**.  
It provides endpoints for managing a collection of games, including creating, retrieving, updating, and deleting records.

---

## Features

- CRUD operations for games
- RESTful API design
- Entity Framework Core integration
- Asynchronous database operations
- DTO-based data shaping
- Relationship handling (Games ↔ Genres)
- Clean and minimal API structure

---

## Tech Stack

- ASP.NET Core (Minimal APIs)
- Entity Framework Core
- C#
- SQL Database

---


### Games Endpoints

| Method | Endpoint       | Description          |
|--------|----------------|----------------------|
| GET    | /games         | Get all games        |
| GET    | /games/{id}    | Get game by ID       |
| POST   | /games         | Create a new game    |
| PUT    | /games/{id}    | Update a game        |
| DELETE | /games/{id}    | Delete a game        |

---

## Future Improvements

React-based frontend to consume the API and provide a full-stack user experience.

---

## ▶️ Getting Started

### Prerequisites

- .NET SDK installed
- SQL Server or compatible database

### Run the project

```bash
dotnet run

