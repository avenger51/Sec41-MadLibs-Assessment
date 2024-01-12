### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
A: React is a JS based that is primarly used for creating web interfaces and dynamic forms.

- What is Babel?
A: Babel is used to convert ECMAScript 2015 code into backwards compatible of JS.

- What is JSX?
A: JSX allows HTML to be written in React.

- How is a Component created in React?
A: A React component are independent and reusable code.  They are created with a JS function or Class.

- What are some difference between state and props?
A:  State is a real time piece of data that can use within a component and a prop is the way that data or properties are passed from component to component.

- What does "downward data flow" refer to in React?
A: Downward data flow describes how data is only passed downwards in the code via props to children components from parent components.

- What is a controlled component?
A: A controlled component is when input data is handled by React state rather than allowing the DOM to manage the data.

- What is an uncontrolled component?
A: An uncontrolled component is where a state is stored internally and is not managed by the React state.

- What is the purpose of the `key` prop when rendering a list of components?
A: A key is a string attribute included in lists of elements.  They identify whice items are changed, updated, or deleted.

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?
A:  Using an array can cause instability because when updated, the index of an item will change.  React could determine this is a different component and re-render.

- Describe useEffect.  What use cases is it used for in React components?
A: useEffect handles the side effects for React when getting data and updating the DOM.  Can run on every render or control the effect of rendering.

- What does useRef do?  Does a change to a ref value cause a rerender of a component?
A: useRef is a way to access or change elements, keep values, and manage the state without causing re-renders.

- When would you use a ref? When wouldn't you use one?
A: If a state needs to re-render, you would not use useRef.

- What is a custom hook in React? When would you want to write one?
A: A customer hook has the benefit of creating useable functionality within components.  You would use a custom hook when you are using JS functions in React.  You would also use when there is a hook or multiple hooks used in multiple locations in the code.