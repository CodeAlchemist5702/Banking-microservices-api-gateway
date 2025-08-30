# Banking-microservices-api-gateway
This repo has code for api gateway.

1. controller->	Contains classes that handle incoming HTTP requests.
2. service-->	Contains business logic, such as route management or token validation.
3. dto-->	Holds Data Transfer Objects that define how data is exchanged between layers.
4. dao-->	Interfaces for data access, often extending JpaRepository or custom repositories for route configurations.
5. entity-->	Maps Java classes to database tables. Represents data stored in persistent storage.
6. filter-->	Defines request/response interceptors for logging, security, etc.
7. config-->	Configuration classes for defining routes and gateway behaviors.
