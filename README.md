# portfolio-project-doc

In this repository there will be architecture design of said project with diagram and explanations of each part of this microesvices architecture project

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

![alt text](https://github.com/xxsawa/portfolio-project-doc/blob/main/portfolio-project-architecture.drawio.png)
