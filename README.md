# portfolio-project-doc

## Goal

In this repository there will be architecture design of said project with diagram and explanations of each part of this microesvices architecture project

## Guidelines of this project

1. Microservices architecture and complimentary technologies used (kubernetes, cloud, on premise, message bus...)
2. OOP design patterns usage in architecture design step
3. Follow Clean code (book) prinicples
4. Test coverage above 90% - naming pattern MethodName_ShouldDoGet_WhenSomething

## Service file structure is

- ./ - service logic
- ./models
- ./controller
- ./otherServiceUsed - can be multiple
- ./otherServiceUsed/models
- ./otherServiceUsed/endpoints

## Service Table

| Is implemented | Services               | Description                                                   | Will be implemented |
| -------------- | ---------------------- | ------------------------------------------------------------- | ------------------- |
| no             | Message bus            | Recieves and sends messages                                   | yes                 |
| no             | User Service           | Handles user authentication and profile management            | yes                 |
| no             | Task Service           | Manages tasks (create, update, delete)                        | yes                 |
| no             | Notification Service   | Sends notifications                                           | yes                 |
| no             | File Upload Service    | Manages file uploads and stores them in blob storage          | yes                 |
| no             | Reporting Service      | Generates reports based on task data                          | yes                 |
| no             | Audit Service          | Logs user actions for audit purposes                          | yes                 |
| no             | Router Service         | Routes incoming api requests onto services (File and User S.) | yes                 |
| no             | Authentication Service | Authenticates incoming requests                               | no                  |
| no             | Search Service         | Provides search functionality for tasks and users             | no                  |
| no             | Comment Service        | Allows users to comment on tasks                              | no                  |

## Architecture Diagram

![alt text](https://github.com/xxsawa/portfolio-project-doc/blob/main/portfolio-project-architecture.drawio.png)

## Credit

Video used for learning [.NET Microservices – Full Course](https://www.youtube.com/watch?v=DgVjEo3OGBI&t=8141s)
