# NZWalks API

## Overview
NZWalks API is a fully functional RESTful Web API that provides sample data for trails in New Zealand. It is designed to offer a comprehensive list of walking trails, including detailed information about each trail.

## Features
- **Retrieve a list of all trails**
- **Get detailed information about a specific trail**
- **Add new trails to the database**
- **Update existing trail information**
- **Delete trails from the database**

## Endpoints
- `GET /api/trails` - Returns a list of all trails.
- `GET /api/trails/{id}` - Returns detailed information about a trail specified by the ID.
- `POST /api/trails` - Adds a new trail to the database.
- `PUT /api/trails/{id}` - Updates the information of an existing trail specified by the ID.
- `DELETE /api/trails/{id}` - Deletes a trail specified by the ID from the database.

## Technologies Used
- ASP.NET Core Web API
- Entity Framework Core
- SQL Server

## How to Run
1. Clone the repository to your local machine.
2. Open the solution in Visual Studio.
3. Restore the NuGet packages.
4. Update the database connection string in `appsettings.json`.
5. Run the application.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
