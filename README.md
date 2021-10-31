# CRA-from-Scratch

This Repo helps you Setup Creating React App Template or Folder Structure without using ```npx create-react-app```

## Understanding CRA under the hood

1. React uses two packages
    * react-dom --> Because React is completely independent of the browser react comes with its own virtual Dom through which, it updates the actual DOM in the browser. ReactDOM is the glue between React and the DOM
    * react --> For everything else, there's React. You use React to define and create your elements, for lifecycle hooks, etc. i.e. the guts of a React application.
