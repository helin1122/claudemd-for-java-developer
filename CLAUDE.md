# Bash commands

# Code style
## tech stack
- language: Java 21 
- Framework: Spring Boot 3.4
- Build tool: Gradle 8.x with Kotlin DSL
- Database: mainly MongoDB, some use MySQL
- Cloud: AWS 
    - ECS, fargate compute engine
    - MongoDB Atlas for MongoDB
    - RDS for MySQL
    - S3 for object storage
    - SQS, AWS Lambda Function for messaging

## Conventions
- favor composition over inheritance
- favor static member class over nonstatic
- perfer interfaces to abstract classes
- don't use raw types
- favor generic methods
- prefer for-each loops to traditional for loops
- prefer primitive types to boxed primitives
- use checked exceptions only for exceptional conditions
    - avoid unnecessary of checked exceptions
    - favor standard exceptions
- leverage **pattern matching** in switch expressions
- use **virtual threads** (Project Loom) for I/O-bound operations
- prefer **Text Blocks** for multi-line strings (SQL, JSON templates)
- use **Stream API** and functional patterns where appropriate

# Workflow
- Be sure to typecheck when you're done making a series of code changes
- Prefer running single tests, and not the whole test suite, for performance
