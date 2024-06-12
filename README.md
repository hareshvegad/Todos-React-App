# Todos React App

This project is a simple Todo list application built with React. It allows users to add, edit, delete, and mark todos as complete. The application utilizes React hooks and context API for state management.

## Features

1. Add new todos: Users can add new todos by typing in the input field and pressing the "Add" button.
2. Edit todos: Users can edit existing todos by clicking on the edit icon next to each todo item, modifying the text, and then saving the changes.
3. Delete todos: Users can delete todos by clicking on the delete icon next to each todo item.
4. Mark todos as complete: Users can mark todos as complete by checking the checkbox next to each todo item.
5. Local Storage: Todos are persisted in the browser's local storage, ensuring that todos remain available even after the browser is refreshed or closed.

## Project Structure

The project consists of the following files and directories:

1. App.js: This is the main component of the application that renders the TodoForm and TodoItem components. It also manages the state of todos using React hooks and provides the TodoContext.Provider for state management.
2. TodoForm.js: This component contains the form for adding new todos. It utilizes the useTodo hook from the contexts.js file to access the addTodo function for adding new todos.
3. TodoItem.js: This component represents a single todo item. It allows users to edit, delete, and mark todos as complete. It also utilizes the useTodo hook to access functions for updating, deleting, and toggling the completion status of todos.
4. contexts.js: This file contains the TodoContext and the useTodo custom hook, which provides access to the todo state and functions for managing todos using the context API.
5. index1.js and index2.js: These files export the TodoProvider, TodoContext, and useTodo hook for use in other components.

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository to your local machine:

git clone https://github.com/hareshvegad/Todos-React-App.git

2. Navigate to the project directory:

cd todos-react-app

3. Install dependencies:

npm install

4. Run the development server:

npm start

5. Open http://localhost:3000 in your browser to view the application.

## Technologies Used

1. React
2. React Hooks
3. Context API
4. HTML
5. CSS

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/my-feature).
3. Make your changes.
4. Commit your changes (git commit -am 'Add new feature').
5. Push to the branch (git push origin feature/my-feature).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.