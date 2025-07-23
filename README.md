# 👨‍💻 Trybe Futebol Clube - TFC

Project developed during the Back-end module of Trybe's Web Development FullStack course, implementing a complete API for football championship management.

## 🚀 Overview

TFC is a system that integrates back-end, front-end and database to provide statistics and rankings for a football championship. The project was developed using:

- **Node.js** with **TypeScript** for back-end
- **Sequelize** as ORM for MySQL database modeling
- **Docker** for service containerization
- **JWT** for authentication
- **TDD** (Test-Driven Development) to ensure code quality

## 🔧 Implemented Features

### ✅ Authentication System
- Login with email and password validation
- JWT token generation
- Token validation for protected routes
- Role-based access control (admin/user)

### ⚽ Teams
- Complete CRUD for teams
- List all teams
- Find team by ID

### 🏆 Matches
- List matches (in progress/finished)
- Create new matches
- Update match scores
- Finish matches
- Validations for match creation

### 📊 Leaderboards
- General team ranking
- Home team ranking
- Away team ranking
- Complex statistics calculation (points, games, victories, etc.)
- Tiebreaker criteria sorting

## 🛠️ Developed Skills

- Application dockerization (containers, networks, volumes)
- Data modeling with MySQL through Sequelize
- Table creation and association using models
- Robust REST API endpoint construction
- CRUD implementation with TypeScript
- Test-Driven Development (TDD)
- Password encryption
- JWT authentication and authorization
- Back-end, front-end and database integration

## ⚙️ Project Structure

The system was developed as a full-stack application with:
- Node.js/TypeScript back-end
- Trybe-provided front-end (React)
- MySQL database
- Everything containerized with Docker and orchestrated with docker-compose
