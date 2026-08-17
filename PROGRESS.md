# Week 1 Progress

## Task 1: Components & Props

### Components

React components are reusable building blocks of a React application. A component can contain its own UI structure and logic. Components are commonly created as JavaScript functions that return JSX.

Functional components are the standard approach for creating React components. They make it easier to divide an application into smaller, reusable parts.

### Props

Props (short for properties) are used to pass data from a parent component to a child component. Props are read-only, meaning a child component should not directly modify the props it receives.

Example:

```jsx
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

function App() {
  return <Welcome name="Saksham" />;
}
```

Here, `name` is passed from `App` to the `Welcome` component as a prop.

### Components vs Props

* **Component:** A reusable UI building block.
* **Props:** Data passed into a component.
* **State:** Internal data that a component can manage and update.

### Setup

The React development environment will be used for the upcoming React track assignments.
