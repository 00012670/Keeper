# Keeper 
Keeper is a simple note-taking web application built with React. It allows users to create, and delete notes.

## Installation
To run Keeper locally, follow these steps:

Clone the repository:
bash
### `git clone https://github.com/00012670/Keeper.git`

Navigate to the project directory:
bash
### `cd Keeper`

Install the dependencies:
### `npm install`

Start the development server:
### `npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Features
Create notes by entering a title and content.
Delete notes by clicking the delete button.
Responsive design to ensure a great user experience on different devices.

## Components
### App
The main component that renders the header, note creation area, note list, and footer. It manages the state of notes and handles note addition and deletion.

### CreateArea
A component that provides a form for creating new notes. It manages the state of the input fields and triggers the onAdd function passed from the parent component when a new note is submitted.

### Note
A component that represents an individual note. It displays the note's title, content, and a delete button. Clicking the delete button triggers the onDelete function passed from the parent component.

### Footer
Displays the copyright information.

## Dependencies
@emotion/react: ^11.11.1
@emotion/styled: ^11.11.0
@material-ui/core: ^4.12.4
@mui/icons-material: ^5.11.16
react: ^18.2.0
react-dom: ^18.2.0
react-scripts: ^5.0.1
web-vitals: ^3.3.2


Runs the app in the development mode.\

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
