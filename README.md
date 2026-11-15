Local Services Discovery & Booking Platform
A learning project that will grow into a portfolio application. The goal is to build a platform where people can discover nearby service providers (such as nail technicians, hairdressers, plumbers, electricians and cleaners) and eventually book appointments.

This project is also my practical way of learning C#, object-oriented programming, databases, Entity Framework Core, ASP.NET Core, APIs, software architecture and frontend development.


Project status
Current version: Version 1 — Console-based service search
I am currently building the first console version. It uses sample provider data and simulated locations. It does not connect to Google Maps or a real database yet. 



Planned versions:

Version 1 — Console-based service search (currently working on)
Build the basic search logic in a C# console application.

Planned features:
- Store a small set of sample service providers.
- Search by service category.
- Search using a location entered by the user.
- Filter providers by a search radius.
- Expand the radius when too few suitable results are found.
- Sort matching providers by distance.
- Allow repeated searches and validate user input.
Learning focus:
- C# fundamentals
- Variables, conditions and loops
- Arrays and List<T>
- Methods and parameters
- Input validation
- Breaking a problem into smaller steps
Not included yet: database, user accounts, real maps, Google APIs, web interface or real bookings.


Version 2 — Object-oriented design and project structure
Refactor the console application into a more organised C# project.

Planned concepts:
- Classes and objects
- Properties and constructors
- Encapsulation
- Enums and collections
- Composition and relationships between objects
- Separating responsibilities across classes and files
- Basic interfaces where they solve a real problem
Possible domain concepts:
- ServiceProvider
- Service
- ServiceCategory
- Location
- SearchCriteria
- Booking

  
Version 3 — Database and Entity Framework Core
Persist application data instead of relying on sample data.

Planned features and concepts:
- SQL Server database
- Entity Framework Core
- DbContext and DbSet
- Entities, primary keys and foreign keys
- Relationships and migrations
- LINQ queries
- Data validation and business rules
- Initial booking and availability data model

  
Version 4 — ASP.NET Core Web API
Expose the application's functionality through HTTP endpoints.

Planned features and concepts:
- ASP.NET Core Web API
- REST principles and HTTP methods/status codes
- Controllers and routing
- Dependency injection
- Application/service layer
- DTOs and validation
- Database integration
- API documentation and testing
- Initial booking endpoints

  
Version 5 — Location and maps integration
Connect the application to real location and places services.

Possible integrations:
- Browser geolocation, with user permission
- Geocoding for typed place names
- Places/business discovery
- Distance-aware search and configurable radius expansion
- Map display and directions context
- API key protection, usage limits and cost awareness
The exact provider and API capabilities will be checked before implementation. External business listings will be distinguished from providers who have registered on this platform.
Version 6 — Frontend and booking website
Build the customer and service-provider experience.

Customer features:
- Search by service and current or manually entered location
- View nearby results, distances and provider profiles
- Filter and view services and prices
- Request or make bookings with registered providers
- View booking history and status
Provider features:
- Register and manage a provider profile
- Add services and prices
- Set availability
- View, accept, decline or manage booking requests
Admin features may include provider review, category management and basic reporting.

The frontend technology will be selected as my React skills develop. The backend remains the main learning focus initially.
Architecture direction
The application will start simple and become more structured as the requirements grow. The intended direction is a modular monolith, not microservices.


Development principles
- Build in small, working increments.
- Understand each feature before moving on.
- Write and debug the code myself; use guidance and code reviews to learn.
- Keep this README updated when a version or feature changes.
- Do not integrate paid or external services before the basic search logic works.
- Add tests as the application becomes more structured.
