# Overview
A group based task management system.

# Todo
- Also allow file upload in the task information page
- Task assignments to groups or multiple people
- request extension for tasks, can also add other reminders, push notifications for tasks
- allow completed tasks of a group to be used to construct another group
    - tasks completed after generation should should feed automatically into the constructed group
- tasks filters (user, etc)
- comments on tasks
- add UI explanations to the mockups
- group "Things to consider" in the mock ups in a future implementations document
- Refactor github directories, maybe keep design documents in a separate branch

# Dependencies
- Production
    - Spring Web
    - Spring Security
    - Spring Data JPA
    - Lombok

- Development
    - H2 Database
    - Spring Boot DevTools
    - Rest Repositories HAL Explorer 

# Usage

# Functionality

# APIs

# Testing

# Available pages
- Task managment page - mockup done
- Task information page - mockup done
- User page (shows assigned tasks and deadlines for tasks) - mockup done
- Group management page -> shows groups managed by user and allows the creation of new groups
- Also team management page (organisation page, who can be added to task groups) -> this can be done later since it would be basically the same as the group page