# SocialMediaApp Readme

## Overview

Welcome to SocialMediaApp, a modern social media application built with Vite, React TypeScript, Tailwind CSS, Shadcn, Tanstack Query, and Appwrite Cloud for the backend. This application aims to provide users with a seamless and enjoyable social media experience.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, ensure you have the following dependencies installed:

- Node.js
- npm or yarn

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/ajeibi/social-media-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd social-media-app
   ```

3. Install dependencies:

   ```bash
   npm install
   # or
   yarn
   ```

4. Create a `.env` file in the root directory and add your Appwrite Cloud API key:

   ```env
   REACT_APP_APPWRITE_ENDPOINT=https://your-appwrite-endpoint/api
   REACT_APP_APPWRITE_PROJECT_ID=your-appwrite-project-id
   REACT_APP_APPWRITE_API_KEY=your-appwrite-api-key
   ```

5. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. Open your browser and visit [http://localhost:3000](http://localhost:3000) to view the app.

## Project Structure

- `src/`: Contains the source code for the application.
  - `components/`: Reusable React components.
  - `pages/`: Individual pages of the application.
  - `styles/`: Stylesheets and Tailwind CSS configurations.
  - `utils/`: Utility functions and helper modules.
- `public/`: Static assets and HTML template.
- `appwrite/`: Appwrite Cloud configurations and services.

## Technologies Used

- [Vite](https://vitejs.dev/): A fast frontend development build tool.
- [React](https://reactjs.org/): A JavaScript library for building user interfaces.
- [TypeScript](https://www.typescriptlang.org/): A superset of JavaScript that adds static typing.
- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework.
- [Shadcn](https://shadcn.com/): A lightweight state management library.
- [Tanstack Query](https://react-query.tanstack.com/): A powerful data-fetching and caching library.
- [Appwrite](https://appwrite.io/): An open-source backend server for web and mobile developers.

## Features

- User authentication and authorization.
- Posting and sharing updates.
- Real-time notifications.
- Friend requests and connections.
- Explore and discover new content.

## Contributing

If you would like to contribute to the project, please follow the [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
