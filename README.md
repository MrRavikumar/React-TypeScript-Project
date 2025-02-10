# Advanced React/TypeScript Note-Taking Application

This project is an advanced note-taking application built with React and TypeScript, featuring markdown support, category-based organization, and filtering capabilities. It is inspired by the tutorial from Web Dev Simplified.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [GitHub Pages](#github-pages)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Markdown Support**: Write and edit notes using markdown syntax for rich text formatting.
- **Categorization**: Organize notes into categories for better management.
- **Filtering**: Easily filter notes by categories or search terms.
- **Responsive Design**: Optimized for various screen sizes, ensuring usability across devices.

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install Dependencies**:

   Using npm:

   ```bash
   npm install
   ```

   Or using yarn:

   ```bash
   yarn install
   ```

### Running the Application

To start the development server:

Using npm:

```bash
npm start
```

Or using yarn:

```bash
yarn start
```

The application will be accessible at `https://mrravikumar.github.io/React-TypeScript-Project/`.

## Project Structure

```
├── dist
├── node_modules
├── public
│   └── vite.svg
├── src
│   ├── assets
│   ├── App.css
│   ├── App.tsx
│   ├── EditNote.tsx
│   ├── index.css
│   ├── main.tsx
│   ├── NewNote.tsx
│   ├── Note.tsx
│   ├── NoteForm.tsx
│   ├── NoteLayout.tsx
│   ├── NoteList.module.css
│   ├── NoteList.tsx
│   └── useLocalStorage.tsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── README.md
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **TypeScript**: Superset of JavaScript for type safety.
- **React Router**: Declarative routing for React applications.
- **React Markdown**: Render markdown in React components.
- **Styled Components**: CSS-in-JS library for styling components.

## GitHub Pages

This project is hosted on GitHub Pages. You can view it live here: [GitHub Pages Link](https://mrravikumar.github.io/React-TypeScript-Project/)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).
