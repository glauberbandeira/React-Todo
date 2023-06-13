# Todo - Task List Application

![Projeto Todo](https://github.com/glauberbandeira/React-Todo/blob/main/img.png)


Todo is a simple yet robust Task List project that allows users to manage their day-to-day tasks. This project was built using React and offers an intuitive user interface, in addition to useful features such as task inclusion and exclusion, marking tasks as complete, task categorization, search functionality, and multi-platform support.

## Main Features

- **Task Inclusion**: Add new tasks to the list quickly and easily.
- **Task Exclusion**: Remove tasks from the list with a single click.
- **Task Completion**: Mark tasks as completed to keep track of progress.
- **Task Categorization**: Group tasks into categories or projects for better management.
- **Task Searching**: Find your tasks by using the search functionality.
- **Intuitive User Interface**: Perform all of the above tasks in an easy and intuitive way.
- **Multi-platform Support**: Access your task list on multiple devices with data synchronization.

## Code Overview

The core of the application is the `App` component. Inside it, you'll find several states:

- `todos` is the state that holds all the tasks.
- `search` is the state used for the search functionality.

The `App` component uses several custom components:

- `Todo`: This component represents a single task in the list.
- `TodoForm`: This component is a form that allows users to add new tasks.
- `Search`: This component allows users to search their tasks.

The `App` component provides the following main functions:

- `addTodo`: It allows users to add new tasks.
- `removeTodo`: It allows users to remove tasks.
- `completeTodo`: It allows users to mark tasks as completed.

## Installation

To run this project locally on your computer, follow the steps below:

### Prerequisites

Before you start, you will need the following tools installed on your machine: 
- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/get-npm)

### Steps

1. Clone this repository using Git:
```git clone https://github.com/glauberbandeira/React-Todo.git

2. Access the project folder:
```cd todo

3. Install the project dependencies:
```npm install
4. Run the application:
```npm start

Now, the application will be available locally at `http://localhost:3000`.

## Contribution

Feel free to contribute to Todo. Create a fork of the project, make your changes, and submit a pull request.