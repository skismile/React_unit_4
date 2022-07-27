# **1. What is React?**

> - React. js is an open-source JavaScript library that is used for building user interfaces specifically for single-page applications. It's used for handling the view layer for web and mobile apps. React also allows us to create reusable UI components.

# **2.Who made React?**

> - React was originally created by Jordan Walke

# **3.What is Babel?**

> - Babel is a JavaScript transpiler, meaning it converts a newer version of ECMAScript, such as ES9, to a standard version (ES5).

# **4.How does Babel convert html code in React into valid code?**

> - With JSX, it is easy to define UI components in React. JSX should not be implemented directly by browsers, but instead requires a compiler to transform it into ECMAScript. This is where Babel comes in. Babel acts as this compiler allowing us to leverage all the benefits of JSX while building React components.

# **5.What is ReactDOM used for? Write an example?**

> - Its a copy of actual Dom,Used for optimization, Is use by react to perform DOM operation faster

# **6.What are the packages that you need to import for react to work with?**

> - react
> - react-dom
> - Bable

# **7.How do you add react to a web application?**

> - Step 1: Add a DOM Container to the HTML
> - Step 2: Add the Script Tags
> - Step 3: Create a React Component
> - render the component

# **8.What is React.createElement?**

> - React. createElement( type, [props], [... children] ) Create and return a new React element of the given type ex-div,h1,etc, props mean Attributes, class,id,events,etc,children mean what is content this tag.

# **9.What are the three properties that createElement accept?**

> - type,props,children

# **10.What is the meaning of render and root?**

> - The term “render” refers to a technique for sharing code between React components using a prop whose value is a function. A component with a render prop takes a function that returns a React element and calls it instead of implementing its own render logic.

> - The root element is the root element of the React DOM tree. It's the element passed to the rendering function ReactDOM. render.
