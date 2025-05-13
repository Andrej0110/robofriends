Robofriends
Robofriends is a simple web application built with React and Vite. It displays a list of robots with their names, email addresses, and profile pictures generated via an API. The app allows users to search and filter the robot list.

![image](https://github.com/user-attachments/assets/b8bbf46a-cd64-4e4d-be4b-e81f884902d3)


Table of Contents

Features
Technologies
Installation
Usage
Project Structure
Deployment
Contributing
License

Features

Displays a list of robot profiles with names, emails, and images.
Search functionality to filter robots by name.
Responsive design for desktop and mobile.
Fast development and production builds with Vite.

Technologies

React: JavaScript library for the user interface.
Vite: Build tool for rapid development and production builds.
JavaScript (ES6+): For application logic.
CSS: For styling.
RoboHash API: Generates unique robot images.

Installation
To run the project locally, follow these steps:

Clone the repository:
git clone https://github.com/Andrej0110/robofriends.git
cd robofriends


Install dependencies:
npm install


Start the development server:
npm run dev

Open http://localhost:5173 in your browser to view the app.


Usage

Search: Enter a name in the search field to filter the robot list.
Interaction: Scroll through the list to view robot profiles.
Production build:npm run build

 The build output will be in the dist folder, ready for deployment.

Project Structure
robofriends/
├── dist/                # Build output (not versioned)
├── node_modules/        # Dependencies (not versioned)
├── public/             # Static assets
├── src/                # Source code
│   ├── assets/         # Images and other resources
│   ├── components/     # React components
│   ├── App.jsx         # Main component
│   ├── index.css       # Global styling
│   ├── main.jsx        # Entry point
├── .gitignore          # Ignored files/folders
├── eslint.config.js    # ESLint configuration
├── index.html          # HTML entry point
├── package.json        # Project dependencies and scripts
├── README.md           # This file
├── vite.config.js      # Vite configuration

Deployment
To deploy the app (e.g., to GitHub Pages):

Create a production build:npm run build


Deploy the dist folder using a hosting service like GitHub Pages, Netlify, or Vercel.
For GitHub Pages, refer to the official documentation.

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (`

