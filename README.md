# Full-Stack JavaScript Challenge

## General Idea

Welcome to the Full-Stack JavaScript Challenge! This project evaluates your programming skills in building a full-stack web application with both frontend and backend components, along with an authentication layer. You will create a simple web app that allows users to input their educational background into their Showwcase profile page.

## What You Will Be Building

Your task is to create a full-stack web application with the following features:

1. Frontend:
   - Create a frontend application using any modern frontend framework of your choice. You can use React, Angular, Vue.js, or any other framework you prefer for building the user interface.
   - Users should be able to enter educational experiences, including Name of School, Degree, Field of Study, Start Year, End Year (or expected), Grade, Description, and any other relevant information.
   - Utilize auto-completion for the school name using an API call.

2. Backend:
   - Set up a backend server using JavaScript (Node.js) with Express. You can use the latest versions of Node.js and Express for your backend development.
   - Implement API endpoints to handle CRUD (Create, Read, Update, Delete) operations for educational experiences.
   - Secure the API with an authentication layer to ensure data privacy.

3. Authentication:
   - Implement user authentication to allow users to register and log in securely.
   - Users should only be able to view, add, edit, and delete their own educational experiences.

## Requirements

- Create a frontend application using any modern frontend framework.
- Set up a backend server using JavaScript (Node.js) with Express.
- Implement user authentication using industry best practices.
- Users must be able to enter as many educational experiences as they please.
- Implement auto-completion for the school name using an API call.
- Users must be able to enter the following information: Name of School, Degree, Field of Study, Start Year, End Year (or expected), Grade, a Description field, and anything else you wish to add.

## Guidance and Instructions

To complete this Full-Stack JavaScript Challenge, you are encouraged to use the latest and most appropriate frontend and backend libraries and tools. While we provide some suggested libraries below, feel free to use any modern technologies that align with your skills and the project requirements.

### Frontend:

- Create a frontend application using any modern frontend framework of your choice. You can use React, Angular, Vue.js, or any other framework you prefer for building the user interface.

- Consider using modern libraries and tools for frontend development, such as:
    - For React: Styled Components ([https://styled-components.com/](https://styled-components.com/)) for styling your components with the power of tagged template literals in React.
    - For Angular: Angular Material ([https://material.angular.io/](https://material.angular.io/)) for UI components and styling.
    - For Vue.js: Vuetify ([https://vuetifyjs.com/](https://vuetifyjs.com/)) for UI components and styling.

- Implement a secure authentication system using the latest authentication libraries for your chosen frontend framework, such as:
    - For React: React Context API or Redux for state management in combination with JWT (JSON Web Tokens) for secure authentication.
    - For Angular: Angular's built-in mechanisms for state management and JWT authentication.
    - For Vue.js: Vuex for state management in combination with JWT authentication.

### Backend:

- Set up a backend server using JavaScript (Node.js) with Express. You can use the latest versions of Node.js and Express for your backend development.

- Use modern libraries for handling API requests and data management, such as:
    - Express with Axios or Fetch API for making API calls and interacting with the database.

- Implement a secure authentication system for the backend using the latest authentication libraries, such as:
    - Passport.js for authentication strategies like JWT (JSON Web Tokens) or OAuth.

### Database:

- Choose a suitable database system (SQL or NoSQL) for storing educational experiences data. Common choices include:
    - PostgreSQL, MySQL, or SQLite for SQL databases.
    - MongoDB, Firebase Firestore, or DynamoDB for NoSQL databases.

- Implement database integration on the backend to store and manage the educational experiences data.

## What We Will Be Looking For

- Functionality: Ensure all required features are working correctly.
- Code Format: Maintain clean and organized code.
- Project Structure: Organize your project in a structured manner.
- Scalability: Design your application to be scalable.
- Maintainability: Write code that is easy to maintain and understand.
- Use of Latest Libraries: Employ modern libraries and tools for both frontend and backend development.
- Authentication Implementation: Implement user authentication securely.

### Some Specific Things We May Be Looking For

- Typescript: Consider using TypeScript for type safety.
- Atomic Design in React: Organize your React components using Atomic Design principles.
- State Management: Implement a state management solution (e.g., Redux) if appropriate.
- Navigation Solution: Correctly implement a navigation solution for the application.
- Componentization: Break down your application into reusable components.
- Communication: Maintain clear communication in your repository and/or code.
- API Calls and Data: Follow best practices for handling API calls and managing data.
- Separation of Concerns: Separate business and UI logic to improve code clarity.
- Frequent Commits: Make frequent and meaningful commits during development.
- Deployment: Deploy the full-stack application to a hosting service (e.g., Vercel, Heroku).

# Goals

Implement the screens based on the wireframes and API provided below, using advanced techniques and industry best practices for your platform. Note that the wireframes may not be complete, so use your best judgment for UI/UX implementation.

## Introduction and Home Screen

- Static text
- Input field for user
- Enter button takes the user to the Main screen

![Image of Introduction Screen](https://github.com/Showwcase/Showwcase-Intern-React-Challenge/blob/master/MacBook_-_2.jpg)

## Main Screen

- Dynamic text
- Button to open up a new modal to add a new education component
- Side panel acts as a bookmark menu of the list of education added
- Each new education added should appear above the previous, i.e., in descending order of most recent

![Image of Main Screen](https://github.com/Showwcase/Showwcase-Intern-React-Challenge/blob/master/MacBook_-_3.jpg)

## Add Education Modal

- Background of Main screen should dim down when the modal opens
- Modal allows the user to add the relevant information and save it.

![Image of Modal Screen](https://github.com/Showwcase/Showwcase-Intern-React-Challenge/blob/master/MacBook_-_4.jpg)

© 2023 Showcase Creators Inc. All rights reserved. Certain information contained herein is derived from information which is protected by copyrights held by Showcase Creators Inc. This code challenge, including any parts of it, cannot be
