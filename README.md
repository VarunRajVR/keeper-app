# Keeper App

Keeper App is a simple note-taking application inspired by Google Keep. It allows users to create, view, and delete notes in an intuitive and user-friendly interface. This project is built using React and Material-UI for styling, and it is deployed using GitHub Pages.

## Features

- Create notes with a title and content.
- Delete notes when they are no longer needed.
- Responsive design using Material-UI components.
- Deployed using GitHub Pages for easy access.

## Demo

You can view the live demo of the app here: [Keeper App](https://VarunRajVR.github.io/keeper-app/)

## Installation and Setup

Follow these steps to run the app locally:

### Prerequisites

- [Node.js](https://nodejs.org/) (version 16 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/VarunRajVR/keeper-app.git
   cd keeper-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```
   This will start the app on a local development server. Open your browser and navigate to `http://localhost:5173` to view the app.

4. **Build the app for production:**
   ```bash
   npm run build
   ```
   The production-ready files will be generated in the `dist` directory.

5. **Deploy the app:**
   ```bash
   npm run deploy
   ```
   Ensure the `homepage` field in `package.json` is correctly set to:

   ```json
   "homepage": "https://<your-username>.github.io/keeper-app/"
   ```

## Technologies Used

- **React**: Frontend library for building user interfaces.
- **Material-UI**: For pre-built React components and styling.
- **Vite**: Development server and build tool for fast performance.
- **gh-pages**: For deploying the app to GitHub Pages.

## Folder Structure

```
keeper-app/
│── public/           # Static assets
│── src/              # Source files
│   ├── components/   # React components
│   ├── App.jsx       # Main application file
│   ├── index.css     # Global styles
│   ├── main.jsx      # Entry point
│── package.json      # Project metadata and dependencies
│── vite.config.js    # Vite configuration
│── README.md         # Project documentation
```


