
# Book Finder Project

## Project Description

The goal of this project is to develop a full-stack web application using the create-react-app with TypeScript and Tailwind CSS that allows users to search for books, and save their favorite books for later reference. This project will showcase your ability to work with modern React.js, TypeScript, Tailwind CSS, and the concepts of decoupled components, hooks, context, DRY (Don't Repeat Yourself), and hexagonal architecture.

## Project Requirements

### Setup

1. Use the create-react-app with TypeScript for your application setup.

2. Integrate the Tailwind CSS into your React application.

### Backend

1. Implement a backend for your application in the language of your choice. This backend should provide APIs (either REST or GraphQL) that your front end can use.

2. Implement login/logout functionality. You can use the free-tier of Auth0 and their SDK, or any other approach you prefer. Make sure to secure your APIs so only authorized users can access them.

3. For storying book data you don't need to use database.  You can load the data from a file that has some sample book infromation and keep everything in memory.

### UI Design

1. Your application should have at least three views: A Login view, a Search view, and a Favorites view.

2. The Login view should provide a way for users to log in to your application.

3. The Search view should include a search bar where users can input the title or author of a book. When the user submits a search, the application should display a list of matching books.

4. Each book in the list should display its title, author(s), and a cover image (if available).

5. Each book item should have a button or link that allows the user to add it to their "Favorites" list.

6. The Favorites view should display a list of all the books that the user has added to their Favorites. Each item in this list should have a button or link to remove it from the list.

### Component Architecture

1. Your application should be structured into decoupled, reusable components using the React.js framework with TypeScript.

2. The state management of the application should be done using React Hooks and Context API.

3. Make sure that your components follow the DRY principle.

4. Aim to adhere to the principles of hexagonal architecture, where appropriate.

### Styling

1. Use Tailwind CSS to style your application. Try to make it as responsive as possible.

2. The application should have a clean, intuitive design. Feel free to use your creativity here.

## Submission

Please submit your project as a Pull Request against the starter repo that has been provided. Make sure to include a README file that explains how to run your application, and any other details you think would be helpful.

Good luck, and happy coding!
