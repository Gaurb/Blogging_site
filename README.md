# Blogging App

## Overview
A full-stack blogging platform. The backend is built with Spring Boot providing REST APIs for users, posts, categories, comments, and JWT authentication. The frontend is a React app using Vite and Appwrite for authentication, database, and storage, enabling user signup/login, post creation/editing, and viewing.

**Live Demo:** [MegaBlog Live](https://megablogging.netlify.app/)

Note: The frontend currently integrates with Appwrite, not the Spring backend. Integration may be needed for full functionality.

## Features
- User authentication (signup, login, roles)
- CRUD operations for posts, categories, comments
- Rich text editing (TinyMCE)
- Responsive UI with Tailwind CSS
- State management with Redux

## Tech Stack
- **Backend**: Spring Boot, Java, MySQL, JWT
- **Frontend**: React, Vite, Appwrite, Redux, Tailwind CSS

## Prerequisites
- Java 20+ (backend)
- Node.js 14+ (frontend)
- MySQL (backend)
- Appwrite instance (frontend)

## Installation and Setup

### Backend (Blogging_backend)
1. Navigate to `Blogging_backend/`
2. Configure database in `src/main/resources/application-dev.properties` (update URL, username, password)
3. Run: `mvn clean install`
4. Start: `mvn spring-boot:run` (defaults to port 8080)

API docs: Access Swagger at `/swagger-ui.html` after starting.

### Frontend (Blogging_frontend)
1. Navigate to `Blogging_frontend/`
2. Install: `npm install`
3. Configure Appwrite in `.env` (copy from `.env.sample` and fill keys)
4. Run: `npm run dev` (runs on http://localhost:5173)

## Usage
- Backend APIs: e.g., POST /api/auth/register, /api/posts, etc.
- Frontend: Signup/login, create/view/edit posts.

## License
MIT License (see LICENSE in frontend).

For questions, check subfolder READMEs or open issues. 