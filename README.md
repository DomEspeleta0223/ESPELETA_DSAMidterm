# Introduction to React.js

`React.js` (commonly known as React) is a popular open-source JavaScript library for building user interfaces (UI), particularly for single-page applications (SPAs). It was `developed by Facebook` and is used for building dynamic, responsive, and reusable UI components.

React makes it easy to build complex UIs by breaking them down into smaller, isolated components that can be managed independently. These components can then be combined to form the overall application UI.

>## Key Features of React:
>- [Component-Based Architecture:](https://www.mendix.com/blog/what-is-component-based-architecture/#:~:text=Component%2Dbased%20architecture%20is%20a,application%20without%20modifying%20other%20components.) React lets you build encapsulated components that manage their own state and can be composed to build complex UIs.
>- [Declarative Syntax:](https://stackoverflow.com/questions/33655534/difference-between-declarative-and-imperative-in-react-js) React's declarative approach makes it easier to design interactive UIs by describing how the UI should look for any given state.
>- [Virtual DOM:](https://www.geeksforgeeks.org/reactjs-virtual-dom/) React uses a virtual DOM to optimize rendering performance by only updating the parts of the UI that have changed.
>- [Unidirectional Data Flow:](https://www.geeksforgeeks.org/reactjs-unidirectional-data-flow/) React enforces a one-way data flow, making it easier to manage state and props.
>- [One-Way Data Binding](https://www.geeksforgeeks.org/reactjs-data-binding/) React uses one-way data binding, meaning data flows in a single direction.

---

## Steps to Get Started with React.js

Follow these steps to create your first React installation.

1. Pre-Requisites 

    Before getting started with React, make sure you have the following installed:
    - `VS Code`: is a powerful, lightweight code editor that provides a rich development environment for React.js, offering features like syntax highlighting, IntelliSense, debugging, and extensions that enhance productivity and streamline development. [Download VS Code Here](https://code.visualstudio.com/).
    - `Node.js`: React requires Node.js to run. You can download and install it from [Node.js official website](https://nodejs.org/).

        ![Node.js Download Interface](https://miro.medium.com/v2/resize:fit:720/format:webp/1*2ScjPOP6RVdmYPEJ_yV-Lw.jpeg)

    - `Npm or Yarn`: npm (Node Package Manager) comes with Node.js, or you can use [Yarn](https://yarnpkg.com/) as an alternative.

    You can check if Node.js and npm are installed by running the following commands in your terminal:
    ```bash
    node -v
    npm -v
    ```

2. Installing Create React App

    The easiest way to get started with React is by using [`Create React App (CRA)`](https://create-react-app.dev/), a tool that sets up a React project with sensible defaults.

    To install CRA globally, run the following command in your terminal:
    ```bash
    npm install -g create-react-app
    ```
3. Creating a New React Project

    Now create a new React application using Create React App:

    ```bash
    npx create-react-app my-first-app
    ```
    This command creates a new directory named `my-first-app` with all the necessary files and dependencies to start working with React.

    Change into the project directory: 
    ```bash
    cd my-first-app
    ```
4. Running Your React App

    To run your React app, use the following command:

    ```bash
    npm start
    ```
    If you used Yarn:

    ```bash
    yarn start
    ```
    This will launch the React development server and open your app in the default browser at http://localhost:3000/. You'll see the default React welcome page.


>Need some further informations to thoroughly understand and follow the instructions? You can watch [`this video`](https://www.youtube.com/watch?v=RVFAyFWO4go).
