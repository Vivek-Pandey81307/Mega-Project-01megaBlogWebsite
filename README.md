# Mega Blog
Welcome to the GitHub repository for the Mega Blog App! This repository contains the source code for a powerful blogging platform equipped with essential features like user authentication, post management, and content creation. It utilizes Appwrite as the backend service for managing the database and storage operations.


## Introduction
Mega Blog is a full-fledged blog application built with React.js that offers the following features:

## Installation

1. Clone the repository

2. Navigate to the project directory

3. Install dependencies: `npm install`

4. Running the Development Server : `npm run dev`

5. Access the application in your browser at `http://localhost:5173` (or the port specified in package.json).

### Appwrite Configuration

- Create an Appwrite account and project at https://appwrite.io.

- Obtain your project's endpoint URL, project ID, and API key.

- Create a `.env` file at the project root and add the following environment variables, replacing placeholders with your actual values:

  1. `VITE_APPWRITE_URL=""`
  2. `VITE_APPWRITE_PROJECT_ID=""`
  3. `VITE_APPWRITE_DATABASE_ID=""`
  4. `VITE_APPWRITE_COLLECTION_ID=""`
  5. `VITE_APPWRITE_BUCKET_ID=""`
  6. `VITE_TINY_EDITOR_API_KEY=""`

### Additional Notes

- Consider adding unit tests and end-to-end tests for robust quality assurance.
- Explore deploying the application to a production environment using a service like Vercel or Netlify.
- Refer to the official documentation for React.js, React Hook Form, TinyMCE, Redux, react-redux, react-router-dom, and Appwrite for detailed usage and configuration guidance.
- This README.md provides a general overview. For a complete understanding, delve into the source code available in the GitHub repository.

## Disclaimer

The information provided here serves as a starting point for understanding the Mega Blog app. While explanations are clear, it's recommended to explore the code itself for the most comprehensive grasp of implementation details.
