# react-intro-vincent

# Intro to React

The moment we all have been wating for is here. Let's get started with React!

<div style="text-align: center;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/2300px-React-icon.svg.png" style="padding-block: 40px; width: 200px">
</div>

<details>
  <summary>Table of content</summary>

- [What is React?](#what-is-react)

- [What does it solve?](#what-does-it-solve)

  - [Declarative Syntax](#declarative-syntax)
  - [Component-Based Architecture](#component-based-architecture)
  - [Virtual Dom](#virtual-dom)
  - [Reusability](#reusability)
  - [Efficient State Management](#efficient-state-management)
  - [Unidirectional Data Flow](#unidirectional-data-flow)
  - [React Hooks](#react-hooks)
  - [Community and Ecosystem](#community-and-ecosystem)
  - [JSX](#jsx)
  - [React Developer Tools](#react-developer-tools)

- [Components In React](#components-in-react)
  - [Return value of components](#return-value-of-components)
- [JSX](#jsx)
- [Props](#props)

</details>

## What is React?

React is a JavaScript library for building user interfaces. It simplifies the process of creating interactive and dynamic UIs by using a component-based architecture and a declarative syntax. React efficiently updates the DOM by leveraging a virtual DOM, resulting in improved performance and a smoother user experience. It is widely used for building modern web applications and is known for its simplicity and reusability of components

[Back to top](#intro-to-react)

## What does it solve?

React offers several features and advantages that make life easier for frontend developers compared to using vanilla JavaScript for complex user interfaces. Here are some key benefits:

[Back to top](#intro-to-react)

### **Declarative Syntax**

React uses a declarative syntax, allowing developers to describe the desired outcome rather than specifying step-by-step how to achieve it. This leads to more readable and maintainable code.

[Back to top](#intro-to-react)

### **Component-Based Architecture**

React promotes a modular and component-based approach to building user interfaces. This makes it easier to manage and organize code, especially in large and complex applications, by breaking down the UI into reusable components.

```jsx
// Vanilla JavaScript (without components)
const header = document.createElement("header");
const title = document.createElement("h1");
title.classlist.add("title");
title.innerText = "My app";
header.appendChild(title);
document.querySelector(".root").appendChild(header);

// React ( with componets )
const Header = () => {
  return (
    <header>
      <h1 className="title">My App</h1>
    </header>
  );
};

ReactDOM.render(<Header />, document.getElementById("root"));
```

[Back to top](#intro-to-react)

### **Virtual DOM**

[Back to top](#intro-to-react)

### **Reusability**

[Back to top](#intro-to-react)

### **Efficient State Management**

[Back to top](#intro-to-react)

### **Unidirectional Data Flow**

[Back to top](#intro-to-react)

### **React Hooks**

[Back to top](#intro-to-react)

### **Community and Ecosystem**

[Back to top](#intro-to-react)

### **JSX**

[Back to top](#intro-to-react)

### **React Developer Tools**

[Back to top](#intro-to-react)

## Components in React

[Back to top](#intro-to-react)

### Return value of Components

[ReactNode vs JSX Element vs ReactElement](https://www.totaltypescript.com/jsx-element-vs-react-reactnode)

[Back to top](#intro-to-react)

## JSX

[Back to top](#intro-to-react)

## Props

[Back to top](#intro-to-react)
