# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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

---

# Pizza Menu Page

This project is a simple React application that displays a pizza menu. It includes components for the header, menu, individual pizza items, and footer. The application is structured in a modular way to make it easy to understand and maintain. This code was learned and written during a course I purchased from Udemy.

## Components

### App Component

The `App` component serves as the main container for the application. It includes the `Header`, `Menu`, and `Footer` components.

### Header Component

The `Header` component renders the header of the page, which includes the title "Pizza Menu Page".

### Menu Component

The `Menu` component displays a list of pizzas. It maps over the `pizzaData` array to create a `Pizza` component for each pizza. If the pizza is sold out, it is not displayed.

### Pizza Component

The `Pizza` component takes a `pizzaObj` as a prop and displays the pizza's image, name, ingredients, and price. If the pizza is sold out, it returns `null` and does not render anything.

### Footer Component

The `Footer` component displays a message based on the current time. It checks if the current time is within the opening hours (9 AM to 5 PM). If the shop is open, it displays a message and a button to order. If the shop is closed, it displays a message with the opening hours.

## Styles

The application uses a CSS file (`index.css`) for styling. Make sure to include this file in your project to apply the styles.

## How to Run

1. Ensure you have Node.js installed.
2. Create a new React application using `create-react-app` or use an existing one.
3. Replace the contents of `src/index.js` with the provided code.
4. Add the `pizzaData` array and all components (`App`, `Header`, `Menu`, `Pizza`, `Footer`) to the same file or split them into separate files as needed.
5. Create an `index.css` file for the styles.
6. Run the application using `npm start`.

## Dependencies

- React
- ReactDOM

These dependencies are included in a standard React setup created using `create-react-app`.

## Learning Source

This code was learned and written during a course I purchased from Udemy. The course provided comprehensive lessons on building React applications, including component-based architecture, state management, and styling.

---

By following the instructions above, you should be able to run and understand the Pizza Menu Page React application. This README provides a high-level overview of the components and their functionality, as well as instructions on how to set up and run the application.
