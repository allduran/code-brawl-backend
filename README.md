# Code Brawl Backend

## Description
Code Brawl is a multiplayer typing game where players type random code snippets from various programming languages. The game increases in difficulty as players score higher. It includes a leaderboard to track top players.

## Tech Stack
- .NET Core
- SignalR (for real-time communication)
- Entity Framework Core (for database access)

## Project Setup

### Prerequisites
- .NET Core SDK (version 5.0 or higher)
- PostgreSQL or MongoDB (depending on your choice)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/code-typer-backend.git
    cd code-typer-backend
    ```

2. Restore dependencies:
    ```sh
    dotnet restore
    ```

### Configuration

1. Configure the database connection in `appsettings.json`.

### Running the Application

1. Start the application:
    ```sh
    dotnet run
    ```

2. The application will be available at `http://localhost:5000`.

### Project Structure

```plaintext
code-typer-backend/
├── Controllers/         # API Controllers
├── Models/              # Data models
├── Services/            # Business logic
├── Hubs/                # SignalR hubs for real-time communication
├── Data/                # Database context and migrations
├── Program.cs           # Entry point
├── Startup.cs           # Configuration
└── ...                  # Other default files
