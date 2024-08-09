
---

# Redux Toolkit Admin Panel

This project is an **Practice-redux-toolkit** built with **React** and **Redux Toolkit**. The application is designed to manage data, leveraging the powerful features of Redux for state management and the simplicity of React for UI development.

## Features

- **Redux Toolkit**: Simplified Redux state management.
- **React-Redux**: Integrated with React for component-based state management.
- **Redux Thunk**: Middleware for handling asynchronous actions.
- **Bootstrap**: Used for responsive and modern UI design.
- **SASS**: Utilized for writing clean and maintainable CSS.
- **UUID**: For generating unique identifiers.
- **JSON Server**: Fake REST API for development and testing.

## Getting Started

### Prerequisites

Ensure you have the following software installed:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [npm](https://www.npmjs.com/) (Comes bundled with Node.js)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/KindrakevychNataly/practice-redux-toolkit.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd practice-redux-toolkit
   ```

3. **Install the dependencies**:

   ```bash
   npm install
   ```

4. **Start the development server**:

   ```bash
   npm start
   ```

   This command will concurrently start the React development server and a JSON server (running on port 3001) which acts as a mock API. Open [http://localhost:3000](http://localhost:3000) to view the application in the browser.

5. **Build the app for production**:

   ```bash
   npm run build
   ```

   The production-ready build files will be created in the `build` folder.

6. **Run tests**:

   ```bash
   npm test
   ```

   This will run the test suite using Jest, configured through `react-scripts`.

### Project Structure

```plaintext
practice-redux-toolkit/
├── public/
├── src/
│   ├── components/     # Reusable UI components
│   ├── features/       # Redux slices and thunks
│   ├── pages/          # Page components
│   ├── App.js          # Main app component
│   ├── index.js        # Entry point for React app
│   └── ...             # Other files and folders
├── .gitignore
├── heroes.json         # Mock data for JSON server
├── package.json
└── README.md
```

### Dependencies

- **`@reduxjs/toolkit`**: Core dependency for managing the app's state.
- **`react-redux`**: Connects React components to the Redux store.
- **`redux-thunk`**: Middleware to handle async actions in Redux.
- **`reselect`**: Selector library for efficient state queries.
- **`bootstrap`**: Framework for building responsive layouts.
- **`sass`**: Preprocessor for advanced styling capabilities.
- **`uuid`**: Generates unique IDs, often used for keys in lists.
- **`classnames`**: Utility for conditionally joining class names.

### Scripts

- **`start`**: Starts the React development server and JSON server concurrently.
- **`build`**: Builds the application for production.
- **`test`**: Runs the test suite using Jest.
- **`eject`**: Ejects the app from `create-react-app` to configure it manually.

### Contributing

Feel free to fork this project and submit pull requests. Any improvements or bug fixes are welcome!

### License

This project is licensed under the ISC License.

---
