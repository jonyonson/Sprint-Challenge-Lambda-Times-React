## Self-Study/Essay Questions

- What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

PropTypes are used to document what the intended type is for any properties passed to React components. During development only, if the type of property passed to a component doesn't match the intended type defined using the PropTypes, then a warning is generated in the consolee.

- Describe a life-cycle event in React?

Life-cycle events occur at different times during the rendering of a component. The three phases of the component life cycle is mounting, updating and unmounting.

- Explain the details of a Higher Order Component?

A higher order component is a function that takes a component as an argument and returns a component with some additonal data or functionality.

- What are three different ways to style components in React? Explain some of the benefits of each.

There are many options for styling React components. One option is just using normal CSS globally and entering the stylesheet reference in the `index.html`. Another option is CSS Modules. CSS modules lets you write CSS normally in a separate file and import the CSS into a specific JavaScript file. A third option is using a library such as Styled Components. Styled Components lets you use Tagged Template Literals to write styles for each specific component.
