# GEMINI Analysis

## Project Overview

This is a minimal React project bootstrapped with Vite. It serves as a starting template for building a web application using the React library and the Vite build tool.

**Key Technologies:**

*   **React:** A JavaScript library for building user interfaces.
*   **Vite:** A modern frontend build tool that provides a faster and leaner development experience.
*   **Tailwind CSS:** A utility-first CSS framework for rapid UI development.
*   **ESLint:** A tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.

**Project Structure:**

*   `index.html`: The main HTML file that serves as the entry point for the application.
*   `src/main.jsx`: The main JavaScript entry point. It renders the root React component (`App.jsx`) into the DOM.
*   `src/App.jsx`: The main application component.
*   `vite.config.js`: Configuration file for the Vite build tool.
*   `package.json`: Defines project metadata, dependencies, and scripts.
*   `eslint.config.js`: Configuration for ESLint.

## Building and Running

The following scripts are available in `package.json` to manage the development lifecycle:

*   **`npm install`**: Installs the project dependencies.
*   **`npm run dev`**: Starts the development server with Hot Module Replacement (HMR).
*   **`npm run build`**: Builds the application for production.
*   **`npm run lint`**: Lints the source code using ESLint.
*   **`npm run preview`**: Serves the production build locally for previewing.

## Development Conventions

*   **Linting:** The project uses ESLint with the recommended JavaScript rules, along with plugins for React Hooks and React Refresh. The configuration can be found in `eslint.config.js`.
*   **Styling:** Tailwind CSS is integrated for styling.
*   **Code Style:** The ESLint configuration enforces a rule to ignore unused variables that start with an uppercase letter or an underscore (`varsIgnorePattern: '^[A-Z_]'`).
