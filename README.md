# portfolio-project-doc

## Goal

In this repository there will be architecture design of said project with diagram and explanations of each part of this microesvices architecture project

## Guidelines of this project

1. Microservices architecture and complimentary technologies used (kubernetes, cloud, on premise, message bus...)
2. OOP design patterns usage in architecture design step
3. Follow Clean code (book) prinicples
4. Test coverage above 90% - naming pattern MethodName_ShouldDoGet_WhenSomething

## Service Table

| Services               | Description                                                   | Will be implemented |
| ---------------------- | ------------------------------------------------------------- | ------------------- |
| User Service           | Handles user authentication and profile management            | yes                 |
| Task Service           | Manages tasks (create, update, delete)                        | yes                 |
| Notification Service   | Sends notifications                                           | yes                 |
| File Upload Service    | Manages file uploads and stores them in blob storage          | yes                 |
| Reporting Service      | Generates reports based on task data                          | yes                 |
| Audit Service          | Logs user actions for audit purposes                          | yes                 |
| Router Service         | Routes incoming api requests onto services (File and User S.) | yes                 |
| Authentication Service | Authenticates incoming requests                               | no                  |
| Search Service         | Provides search functionality for tasks and users             | no                  |
| Comment Service        | Allows users to comment on tasks                              | no                  |

## Architecture Diagram

![alt text](https://github.com/xxsawa/portfolio-project-doc/blob/main/portfolio-project-architecture.drawio.png)
