# Task Management Application

The Task Management application is a robust and user-friendly web-based application developed using Spring Boot and Java. It provides users with a seamless and efficient platform to create, organize, and manage tasks effectively. Whether it's personal task management or team collaboration, this application offers a comprehensive set of features to streamline task management processes. Users can easily create tasks by providing relevant details such as the task title, description, assigned person, and status. They can view all tasks at a glance, including important information like task descriptions, assigned individuals, and current statuses. Additionally, users have the flexibility to update task statuses as tasks progress, ensuring accurate tracking and improved productivity. With its intuitive interface and powerful functionality, the Task Management application simplifies task management, enabling users to stay organized and focused on their goals.

## Features

The Task Management Application offers the following features:

1. **Create Tasks**: Users can create new tasks by providing essential details such as the task title, description, assigned person, and status.
2. **View Tasks**: The application displays a list of all tasks, including their titles, descriptions, assigned persons, and statuses.
3. **Update Task Status**: Users can update the status of a task to reflect its progress. They can choose from the available status options: Pending, In Progress, and Completed.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- HTML
- CSS
- JavaScript
- RESTful API

## Getting Started

To get started with the Task Management application, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/AVBalajee/Spring-Boot-Projects.git

2. Navigate to the project directory:
   ```bash
   cd TaskMgmt
   
3. Build and run the application using Maven:
   ```bash
   mvn spring-boot:run
   #Open your web browser and access the application at http://localhost:8080/task.html

## Usage

### Create a Task

To create a new task, follow these steps:

1. Fill in the required fields in the "Create New Task" form located on the main page.
2. Provide the following details for the task:
   - **Title**: Enter a descriptive title for the task.
   - **Description**: Provide additional details or instructions for the task.
   - **Assigned To**: Enter the name or username of the person assigned to the task.
   - **Status**: Select the current status of the task from the available options (e.g., Pending, In Progress, Completed).
3. Once all required fields are filled, click the "Create Task" button.
4. The task will be created and added to the task list displayed below the form.

### View Tasks

To view the list of all tasks, simply scroll down on the main page. The task list will be displayed, showing the following information for each task:

- **Title**: The title of the task.
- **Description**: Additional details or instructions for the task.
- **Assigned To**: The name or username of the person assigned to the task.
- **Status**: The current status of the task.

### Update Task Status

To update the status of a task, follow these steps:

1. Locate the task in the task list for which you want to update the status.
2. Next to the task, you will find an "Update" button. Click on it.
3. A prompt will appear asking you to enter the updated status for the task.
4. Enter the new status in the prompt and click "OK" to confirm the update.
5. The task's status will be updated in the UI, and you will see the updated status reflected in the task list.

Note: The status options available for selection when creating or updating a task are: Pending, In Progress, and Completed.


