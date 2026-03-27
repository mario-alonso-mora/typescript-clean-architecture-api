# TypeScript Clean Architecture API

Scalable REST API built with TypeScript and Express following a clean three-layer architecture.  
Designed to demonstrate separation of concerns, maintainability and extensibility in backend systems.

---

## Architecture Overview

This project follows a structured architecture divided into three main layers:

- **Controllers** → Handle HTTP requests and responses. Responsible for input validation and delegating logic.
- **Services** → Contain business logic and application rules.
- **Repositories** → Manage data access and persistence.

### Request Flow

Client → Controller → Service → Repository → Data Source

---

## Tech Stack

- TypeScript
- Node.js
- Express

---

## Key Principles

- Separation of concerns
- Modular design
- Scalable structure
- Maintainable codebase
- Ready for integration with databases or external services

---

## Project Structure
