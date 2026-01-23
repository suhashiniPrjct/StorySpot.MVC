# The Story Spot (ASP.NET Core MVC)

## Overview
ASP.NET Core MVC application built on .NET 8 for managing and browsing books.  
This is a **standalone MVC application** with a dedicated **data access layer** using **Entity Framework Core (Code First)**, following clean architectural practices expected in production applications.

## Key Features
- Identity-based authentication (User / Admin) 🔐
- Role-based authorization
- Book management (CRUD)
- Repository & Unit of Work patterns
- EF Core (Code First) data access
- Responsive, clean MVC UI

## Architecture
- Browser → MVC Application → Database 🧱
- Authentication and authorization via ASP.NET Core Identity
- Data access encapsulated in a dedicated data layer
- Clear separation of concerns for maintainability

## Tech Stack
- ASP.NET Core MVC 8
- Entity Framework Core
- ASP.NET Core Identity

## Best Practices
- MVC pattern for UI and controller separation
- ViewModels to decouple UI from domain models
- Repository & Unit of Work for data abstraction
- Optimized EF Core queries (AsNotracking(), includes(), filtering)
- Data annotations for validation and schema consistency
- Clean, maintainable, test-friendly codebase
- Cloud-compatible design ☁️ (Azure App Service tested)

## Planned Architecture Enhancement
- Data access layer to be exposed via a dedicated Web API 🔁
- MVC application to act purely as the presentation layer
- API to handle business logic and persistence
- Secure service-to-service communication 🔒

## Potential Enhancements
- Improved UI/UX and accessibility
- Pagination and advanced search
- Logging and monitoring integration 📊

## About the Developer 👨‍💻
I am an experienced .NET developer specialising in Microsoft technologies, including:
- C#
- ASP.NET Core & ASP.NET MVC
- ASP.NET Web API
- ASP.NET Framework
- Entity Framework Core
- LINQ & SQL Server
This API demonstrates my ability to design and implement secure, scalable backend services using current .NET frameworks and industry-standard best practices.
