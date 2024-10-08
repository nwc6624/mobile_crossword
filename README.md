# Basic react crossword app project

# demo image as of 10/2/24
![image](https://github.com/user-attachments/assets/314c6672-191e-4952-bf2a-3b6cf3442c96)

![image](https://github.com/user-attachments/assets/f5143d44-12ce-4181-afaa-ce2e31f96021)
![image](https://github.com/user-attachments/assets/dc57bf78-c337-4cfc-a06a-f1cf9984a61b)





**React**: Frontend framework for building interactive user interfaces. <br />
**React DnD**: Enables drag-and-drop functionality for interactive gameplay.<br />
**Axios**: Used for making HTTP requests to fetch random words from the API.<br />
**JavaScript (ES6)**: Core language for logic and interactivity.<br />

**CSS**: Styling for the crossword game layout and components.<br />
**Random Word API**: Provides random words to challenge the player.<br />
# This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).<br />

## Features
**Drag or Click Letters:**<br />

Players can drag letters from the bank to the blanks or simply click them to place them in the leftmost empty slot.
Once a letter has been used, it turns red and becomes unselectable.<br />
**Check for Correctness:**<br />

When the "Check" button is pressed, a popup will inform the user if the word is correct or how many letters are wrong.
If the word is spelled incorrectly, the player can opt to receive a hint, where a blank or incorrect letter will be filled in automatically.<br />
**Get New Words:**<br />

When the player completes the word correctly, they are given the option to fetch a new word and continue playing.<br />
**Hints System:** <br />

Players can ask for hints if the word is spelled incorrectly. The hint will fill in a correct letter in the word and mark the corresponding letter as used.<br />


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

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

## Project Structure
/src: Contains all source code, including the main components like App.js and styling in App.css. <br />
/public: Contains the public assets and the index.html file, which is the entry point for the React application.<br />

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
