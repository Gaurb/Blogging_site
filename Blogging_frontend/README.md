# MegaBlog

![MegaBlog Logo](./src/assets/react.svg) <!-- Replace with actual logo if available -->

## Overview

MegaBlog is a modern, full-featured blog application built with React and Vite, powered by Appwrite for backend services. It allows users to create accounts, authenticate, and manage blog posts with a rich text editor. The application features a clean, responsive UI and handles user sessions efficiently.

## Live Demo

Check out the live application at [MegaBlog Live](https://megablogging.netlify.app)

## Features

- **User Authentication**: Secure signup, login, and logout functionality using Appwrite.
- **Post Management**: Create, edit, delete, and view blog posts.
- **Rich Text Editing**: Integrated RTE using TinyMCE for formatting posts.
- **Responsive Design**: Mobile-friendly interface with Tailwind CSS.
- **State Management**: Uses Redux Toolkit for handling application state, including authentication status.
- **Routing**: Managed with React Router for seamless navigation.
- **Form Handling**: Utilises React Hook Form for efficient form management.

## Technologies Used

- **Frontend Framework**: React.js
- **Build Tool**: Vite
- **Backend Services**: Appwrite (authentication and database)
- **State Management**: Redux Toolkit, React Redux
- **Styling**: Tailwind CSS
- **Routing**: React Router DOM
- **Rich Text Editor**: TinyMCE React
- **Form Library**: React Hook Form
- **Other**: HTML React Parser

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- Appwrite instance (self-hosted or cloud)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Blogging_frontend.git
   cd Blogging_frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Copy `.env.sample` to `.env`
   - Fill in your Appwrite project details (e.g., APPWRITE_ENDPOINT, APPWRITE_PROJECT_ID, etc.)

4. Start the development server:
   ```bash
   npm run dev
   ```

   The app will be available at `http://localhost:5173` (or the port specified by Vite).

## Usage

- **Signup/Login**: Navigate to the signup or login page to create an account or log in.
- **Create Post**: Once logged in, go to the "Add Post" page to create a new blog post using the TinyMCE editor.
- **View Posts**: Browse all posts on the "All Posts" page or view individual posts.
- **Edit/Delete**: Edit or delete your own posts from the post details or edit page.

## Configuration

Appwrite configuration is handled in `src/appwrite/config.js` and environment variables in `.env`. Ensure all required keys are set correctly.

## Scripts

- `npm run dev`: Start development server
- `npm run build`: Build for production
- `npm run lint`: Run ESLint
- `npm run preview`: Preview production build

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature').
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

Please ensure your code adheres to the project's ESLint rules.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. (Note: If no LICENSE file exists, add one or specify accordingly.)

## Contact

For questions or feedback, open an issue on GitHub or contact the maintainer.
