# LinguaFlow

A comprehensive language learning application built with .NET 8, featuring a Windows desktop application, web API, and web server components.

## Overview

LinguaFlow is a full-stack language learning platform that provides interactive courses, quizzes, and progress tracking. The application consists of multiple components working together to deliver a seamless learning experience.

## Architecture

The solution is built using a modular architecture with the following components:

### Core Components

- **DuoClassLibrary**: Shared class library containing models, services, and business logic
- **Duo.Api**: RESTful API built with ASP.NET Core 8.0
- **Duo**: Windows desktop application using WinUI 3
- **WebServerTest**: Web server component for course management
- **Test Projects**: Comprehensive test suites for all components

## Features

### Learning Management
- **Course System**: Structured language courses with difficulty levels
- **Section-based Learning**: Organized learning paths with progressive difficulty
- **Quiz System**: Interactive assessments to test knowledge
- **Exam System**: Comprehensive evaluations for course completion

### User Experience
- **User Authentication**: Secure login and registration system
- **Progress Tracking**: Monitor learning achievements and completion rates
- **Streak System**: Daily learning motivation through streak tracking
- **Coin System**: Virtual currency for course purchases and rewards
- **Leaderboards**: Competitive learning through ranking systems

### Social Features
- **Friend System**: Connect with other learners
- **Post Sharing**: Share learning achievements and experiences
- **Comment System**: Interactive discussions on learning content
- **Hashtag Support**: Categorized content discovery

### Technical Features
- **Entity Framework Core**: Data persistence with SQL Server support
- **Identity Management**: Secure user authentication and authorization
- **Dependency Injection**: Modular service architecture
- **AutoMapper**: Efficient object mapping
- **Swagger/OpenAPI**: API documentation and testing

## Technology Stack

- **.NET 8.0**: Latest LTS version for optimal performance
- **WinUI 3**: Modern Windows desktop UI framework
- **ASP.NET Core**: High-performance web framework
- **Entity Framework Core**: Object-relational mapping
- **SQL Server**: Robust database backend
- **AutoMapper**: Object mapping utilities
- **StyleCop**: Code quality and consistency

## Project Structure

```
LinguaFlow/
├── DuoClassLibrary/          # Shared business logic and models
├── Duo.Api/                  # REST API endpoints
├── Duo/                      # Windows desktop application
├── WebServerTest/            # Web server component
├── DuoClassLibrary.Tests/    # Unit tests for class library
├── Duo.Api.Tests/            # API endpoint tests
└── TestProject1/             # Additional test components
```

## Getting Started

### Prerequisites
- Visual Studio 2022 or later
- .NET 8.0 SDK
- SQL Server (for production) or SQL Server Express
- Windows 10/11 (for desktop application)

### Building the Solution
1. Clone the repository
2. Open `Duo.sln` in Visual Studio
3. Restore NuGet packages
4. Build the solution
5. Run the desired project

### Configuration
- Update connection strings in configuration files
- Configure user secrets for development
- Set up database migrations if needed

## Development

The project follows modern .NET development practices:

- **Clean Architecture**: Separation of concerns with layered design
- **Dependency Injection**: Service-oriented architecture
- **Repository Pattern**: Data access abstraction
- **DTO Pattern**: Data transfer objects for API communication
- **Validation**: Input validation using data annotations
- **Error Handling**: Comprehensive exception management

## Testing

Comprehensive test coverage across all components:
- Unit tests for business logic
- Integration tests for API endpoints
- Mock-based testing with Moq framework
- MSTest framework for test execution

## Deployment

### Desktop Application
- MSIX packaging for Windows Store deployment
- Self-contained deployment options
- Platform-specific builds (x86, x64, ARM64)

### Web Components
- Docker containerization support
- Azure deployment ready
- Environment-specific configuration

## Performance

- **Optimized Queries**: Efficient database operations
- **Caching Strategies**: Performance optimization
- **Async Operations**: Non-blocking I/O operations
- **Memory Management**: Efficient resource utilization

## Security

- **Identity Framework**: Secure authentication
- **Password Hashing**: Secure credential storage
- **Input Validation**: Protection against malicious input
- **HTTPS Enforcement**: Secure communication protocols

## Monitoring and Logging

- **Diagnostic Information**: Comprehensive logging
- **Performance Metrics**: Application performance tracking
- **Error Reporting**: Detailed error logging and reporting
- **User Activity Tracking**: Learning progress monitoring

## Future Enhancements

- **Mobile Applications**: Cross-platform mobile support
- **AI Integration**: Personalized learning recommendations
- **Offline Support**: Learning without internet connection
- **Multi-language Support**: Interface localization
- **Advanced Analytics**: Detailed learning insights
- **Gamification**: Enhanced reward systems

## License

This project is developed for educational and demonstration purposes.
