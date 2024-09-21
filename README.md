# React Foundations

This repository contains the code and exercises completed during the [React Foundations](https://nextjs.org/learn/react-foundations) course. The course focuses on learning the fundamentals of React and Next.js, two key tools for modern web development.

## Contents

The project is divided into different branches, each representing a chapter of the course. Below is an overview of what was implemented in each branch:

- **branch `chapter-03`**: Updating UI with JavaScript.
- **branch `chapter-04`**: Getting Started with React.
- **branch `chapter-05`**: Creating components and Nesting components.
- **branch `chapter-06`**: Using props, Object destructuring, Using variables in JSX, and Iterating through lists.
- **branch `chapter-07`**: Handling events and State with hooks.
- **branch `chapter-09`**: Installing Next.js, Creating your first page, and Running the development server. **Error**: The `useState` hook cannot be executed on the server and must be moved to the client.
- **branch `chapter-10`**: Server and Client Components (errors from the previous branch fixed).

## Installation

If you want to clone the project and explore the code, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/mrearsbig/react-foundations.git
   cd react-foundations
   ```

2. **To install dependencies**:

   - Dependencies can only be installed starting from **branch `chapter-09`** or later, as these branches contain the `package.json` file required for dependency installation:
   
     ```bash
     git checkout chapter-09  # or branch `chapter-10`
     npm install
     ```

3. **To run the application**:

   - **branch `chapter-09`**: Contains an error where the `useState` hook is incorrectly executed on the server, but can still be run.

     ```bash
     git checkout chapter-09
     npm run dev
     ```

   - **branch `chapter-10`**: The error from the previous branch has been fixed, moving the `useState` hook to the client, and the application runs without issues.

     ```bash
     git checkout chapter-10
     npm run dev
     ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Additional Resources

- [React Documentation](https://react.dev/)
- [React Foundations](https://nextjs.org/learn/react-foundations)
