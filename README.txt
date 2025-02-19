# Southwest_Airline_Interview_Questions

Q1: Features build? 

Vijay Nimmagadda here, Austin, Texas.
I am a core UI Developer with 10+ years of experience building .com websites for different organizations using HTML5, CSS3, JavaScript, React.js, and Redux. 
In the past 2 years, I worked on the React migration team, where I converted the .net pages to react on united.com. 
Frontend is React, and used ATMOS (Own library) components used company wide.

Worked on Security features for users where they can manage there account like Forgot password, Forgot MileagePlus number, security questions, Sign-in features, Miles-Pooling, United Club pass,  Recent Activity, dashboard updates and KTN(Known Traveler Number), Accessibility guidelines features on united.com.

used middleware such as redux-saga to handle asynchronous tasks such as API calls, data fetching, and impure actions in a more organized and efficient way.

The new initiative worked on Miles-Pooling( points you get after traveling), TSA Precheck, Account security and management features, and Under18.

Previously worked with Accelerator team for Visa Inc. remediation of MBDA modules like Application Management, Account Management, Portfolio Management, Analytics, Recurring billing, Virtual Terminal, etc for bank users like Wells Fargo,  Bank of America, etc

Capital Group worked on DAVIS Project. Davis stands for Data visualization where we build different highcharts using react and integrate into the AEM., the backend is Java. Previously I worked on Creative Workbench, a writing tool where articles are published on capital group websites.

At Cerner Corporation worked on the medical examination forms.

In Office Depot worked on black Friday reporting.

Satinos Technologies created a tax portal and a schoomin website for the Vignan schools.

Q2: how the daily scrum meetings were:  
15 minutes what we did yesterday, today, if there is blocker discuss it end of the meeting. Chat button, integrarted it is not working, backend team asked need to meet pre-conditions. Works on environment dev, staging in particular time 9am -9pm EST.


Q3: Size of the team: 10, 3 fe, 3be, 2QA, 1 scrum master, 1 manager, 1 lead, 3 product owners from myTeam

Q4: what part you played: Senior UI Developer
Q5: how you take initiative on the work flow/ features. They like the leadership and mentoring.
Mentored the new joines on how the app works and architecture, share confluence notes I prepared. 
code review done with peers.
I took care of the release stuff and mostly new Epic Branch after the release.

q6: Code Reviews: 
naming convention is checked. 
Don’t repeat yourself. 
If we can convert the particular logic functional component into new Hook which can reused. Ex: Use Screensize hook to check desktop, mobile or tablet.
If the code is company standards or architecture – Containers, components, folder structure has been organized.

q7: client facing projects: All projects – United.com
q8: ecommerce: office depot – black Friday reporting
q9: mobile vs internal applications
I have done personal projects on react native for learning purposes. It mostly uses React-EcoSystem.  We don’t use <div><p> but mobile components from react native library like <TEXT> <VIEW><ScrollView>

q10: He will also ask about your interest in being in the Dallas/Fort Worth area and will reconfirm when you are willing to relocate to the area. YES

===========================================================

Challenges? 
Initially worked on Sign-in features where the account gets locked if you answer 2 questions wrong. Then the account is hard locked.
I need to request a backend developer unlock it. I have created a list of steps needed to unlock and account where it has a bunch of calls within Postman and made it simple.

Tickets?  Dotcom migration stories, MyAccount, and MyUnited new features added.
Start? End?  
I started as a UI Engineer and worked as Scrum Master and Release specialist have done more 35+ releases so far.

========================================

Interview Questions:

1. How are you doing?
I am Vijay Nimmagadda. nice to meet you. absolute pleasure. Started my career with html, css. i love what i do.

2. Tell me about yourself? project? language? expertise.
working on past 10 years, moved from company to company as contractor. i have to use different technologies. recently i was working on Javascript.
current working on React migration team, where I converted the .net pages to react. 

3. technologies used?
frontend is react

4. do you use any other framework?
no, just react.js 

5. Is your project build on class based or functional based components?
It is a recent project. lot of times we have to deal with legacy code. I have to use functional components.


6. do you have experience in class-based components? years

7. if you starting new project today? which components will you use?
For most use cases, functional components with Hooks are the recommended approach.
Use class components when you need advanced features like lifecycle methods or error boundaries.
Consider the complexity of your component, the size of your project, and your team's familiarity with the different approaches.

8. How does React.js work? React virtual DOM work?
First for HTML <p> tag <div> does some things. ability to use html components with added functionality with JS.

A virtual DOM object has the same properties as a real DOM object, but it lacks the real thing's power to directly change what's on the screen. Manipulating the DOM is slow. 
Manipulating the virtual DOM is much faster, because nothing gets drawn onscreen.

9. Virtual DOM is not build by React? is there any other library use Virtual DOM?
Vue.js - virtual DOM

10. button click --> using react hooks, 4 call set states will react update the states? name? avatar? calculate?
there will be optimization. it will re-render

11. what kinds of tools used for state management?
redux  used to implement the "state management".
We have redux thux, redux saga.
redux saga? Inorder to manipulate the store Actions(request, response).
Redux thunx is an outdated library.
Saga is Advanced library.

Redux is a predictable state container for JavaScript applications. It helps to you write applications, run in different environments and easy to test. 
And simply we called as Redux is a state management tool.
Components in redux
Actions -->Input Parameters Ex: Deposit and Withdraw money from ATM
Store --> Main Server
Reducers --> Business Logic
Dispatch --> Request
Subscribe --> Response
State --> Store Component Data

12. any tools used for debugging tools? extensions?
redux dev tools - chrome extensions

13. what are the best practices to test react application?
data flow is undirectional in react app. using test library to test the states.
Enzyme, JEST for unit testing. add 80% coverage for the files.

14. do you have any experience deploying React applications.
yes i have used autodeploy in united.com, AWS for capital group.

15. do you have experience in docker?
yes worked on it long back. we can mirror the production inside it. run react.js it is much more easy.

16. what are the best practice to use React.js?
it depends, varies from company to company
modularizing the react components. 
using the linter.
for event handler onclick camelcase is better.
using ES6 syntax is good.
prefering functional components over class components.

17 what do you understand of code splitting?
insteading of loading entire JS code. it is easy to split, components that are not required in the initial page.

18. how can we exactly do code splitting?
don't import functional components.
load component by component.
create small component by webpack
performance is important.
==============================================================================

Interview 2:

1. Hello, vijay? how is your day?

2. tell me little bit about your background, and experience.
i am working for united.com
In the past 2 years, I worked on the React migration team, where I converted the .net pages to react. 
Frontend is React, backend is Java and used ATMOS library for CSS styling.
Worked on Forgot password, Forgot MileagePlus number, security questions, Sign-in features, Miles-Pooling, United Club pass,  Recent Activity, dashboard updates and KTN(Known Traveler Number), Accessibility guidelines features on united.com.
used middleware such as redux-saga to handle asynchronous tasks such as API calls, data fetching, and impure actions in a more organized and efficient way.
The new initiative worked on Miles-Pooling( points you get after traveling), TSA Precheck, Account security and management features, and Under18.

3. What is new in React.js 18?
concurrency,
automatic baching.
useag,
suspense on server
hooks
api 
create route
hydrate route
strict mode.

4. react.js 17 upgrade 18 steps to follow
change the index.js file
previous reactdom.render Now Reactdom.createRoute

5. What is Automatic batching in react 18?
react 18 batches the setTimeout, promises, callback

6. what are transitions? how are they different from debouncing from setTimeout?

transition new Feature in React 18, it doesn't freeze your screen previous it used to stop.
transition takes a low-priority que and executes. 
setTimeout with transition we can't do that.

7. What is suspense on the server?
it comes from next.js from react. Now react18 is to add the functionality.
server side rendering.
Now react 18, server side rendering will display on the screen.

8. What is reconciliation?
react compares the actual page/ DOM to possibility different one. if it requires the update renders the DOM.
Comparision between the DOM.

List of users, map(), for loop --> add key props

9. Higher order component? HOC
 higher-order component (HOC) is an advanced technique in React for reusing component logic.
Concretely, a higher-order component is a function that takes a component and returns a new component.
const EnhancedComponent = higherOrderComponent(WrappedComponent);

helps reusability.
adds functionality
react redux we use connect

10. what are hooks used in HOC? 
we use custom hooks for reusability

11. techniques to improve performance?
react.memo - memoize entire component.
useMemo, useCallback to store.
lazy loading - load the component when the screen is loaded.

12. what is key architecture difference between react and angular?
angular is framework need to follow the convention, in react we use Virtual DOM and 1 -way data binding. angular uses real DOM, 2-way data binding.

13. why render? how to prevent re-rendering
props or state of component change it will re-render. 
we can prevent shouldComponentUpdate method.
use hooks like usecallback, usememo for re-rendering.

================================================================

Worked on hooks like useState, useEffect, useContext, and useReducer to manage state and side effects in functional components. 
useState
Storing form input values
Toggling UI elements (e.g. modals, dropdowns)
Maintaining component-specific data.

useEffect
Fetching data from an API
Setting up event listeners
Updating the document title
Cleaning up resources (e.g. cancelling subscriptions)

useContext
Theming
User authentication state
Localization


useReducer
Complex state updates
When state logic becomes too complicated for useState
Managing form state with multiple fields

===============================================================
## Southwest Airlines 

### Introduction questions
- Introduce yourself ?
In past 2 years worked on React migration team where I converted the .net pages to react in united.com 
Frontend is React, backend is Java. Used ATMOS library for CSS styling.
Worked on Forgot password, Forgot MileagePlus number, security questions, Sign-in features, Miles-Pooling, United Club pass,  Recent Activity, dashboard updates and KTN(Known Traveler Number) , Accessibility guidelines features on united.com.
New initiative worked on Miles-Pooling( points you get after traveling), TSA Precheck, Account security and management features, Under18.



- How did it all started, when did you decide you wanted to be frontend developer.
I have started as a UI Engineer and worked as Scrum Master and Release specialist have done more 35+ releases so far.


- What is your primary skill, list your skills in order of proficiency.

React.js, 
Redux-Saga, 
JavaScript, 
JSON, 
Ajax, 
HTML5, 
CSS3, 
Node.JS, 
Rest, 
Visual Studio Code, 
Git/GitHub, TeamCity, 
Postman, 
Confluence, 
Agile, 
UI Analytics (Google Analytics, Quantum Metrics), 
Mobile Web Technologies



- what did you feel about the transition from mobile development into web development.


---
### HTML questions
- What are semantic tags in HTML, what is the importance of using them ?

Semantic tags in HTML are specific HTML elements that describe the meaning and purpose of the content they enclose, rather than just how it looks, 
providing context to both developers and machines like search engines and screen readers, making the web page structure more understandable and accessible; 
essentially, they convey the "semantics" or meaning of the content on a page, going beyond just visual presentation. 

• Examples of semantic tags: <header>, <nav>, <main>, <section>, <article>, <aside>, <footer> 
• Benefits of using semantic tags:
	• Improved accessibility: Screen readers can better interpret the page structure and read content meaningfully. 
	• Better SEO: Search engines can understand the content hierarchy and relevance more accurately, potentially improving search rankings.
	• Code readability: Makes HTML code clearer and easier to maintain for developers.


- What is inline element vs block level elements ?
Every HTML element has a default block-level or inline behavior. 
Paragraphs are block-level elements, which means that they block off a whole line for themselves, 
and images are inline elements, which means they will automatically be placed next to one another on the same line.

- What is `inline-block` ? Why is it used ?
"Inline-block" is a CSS property value used to set the display style of an element, 
allowing it to behave like an inline element (flowing with text) while also enabling the ability to set specific width and height values, similar to a block element
---
### CSS Question

- What are different positions in CSS ?
The position property specifies the type of positioning method used for an element.

There are five different position values:

static: HTML elements are positioned static by default.

relative: An element with position: relative; is positioned relative to its normal position.

fixed: An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. 
The top, right, bottom, and left properties are used to position the element.

absolute: An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

sticky: An element with position: sticky; is positioned based on the user's scroll position.
---
### Javascript Questions
- What is the difference between var, let and const ?

var is function-scoped, while let and const are block-scoped. A block is a section of code contained within curly braces, such as an if statement or for loop.
var and let variables can be reassigned, but const variables cannot.
var variables are initialized with undefined, while let and const variables are not. However, var and let can be declared without being initialized, while const must be initialized during declaration.
var variables are hoisted, meaning they can be accessed before they are declared, but let and const variables are not.


- What is hoisting ?
In JavaScript, hoisting is a behavior where variable and function declarations are moved to the top of their scope before code execution. 

- What is ES6 arrow functions ?
ES6 arrow functions are a concise syntax for writing functions in JavaScript, introduced in the ECMAScript 2015 (ES6) standard, which allows for shorter, 
cleaner code by using the "fat arrow" notation (=>) to define a function without the need for the traditional "function" keyword, 
making them particularly useful for creating anonymous functions and passing functions as arguments to other functions.

- What is self invoking function and why is it useful ? what are some of the useCases ?
A "self-invoking function" (also known as an Immediately Invoked Function Expression - IIFE) is a function that executes automatically as soon as it is defined, 
essentially running its code immediately without needing to be explicitly called;

---
### React Questions
- How do you optimize the React components ?

Memoization:
React.memo:
Use React.memo to wrap functional components and prevent unnecessary re-renders when props haven't changed.
useMemo:
Use useMemo to memoize expensive calculations that depend on specific values, avoiding recalculation on every render.
useCallback:
Use useCallback to memoize callback functions, ensuring they aren't recreated on each render unless their dependencies change.
Code Splitting and Lazy Loading:
React.lazy:
Use React.lazy and Suspense to dynamically import components only when needed, reducing initial bundle size and improving load times.
Webpack/Rollup:
Use bundlers like Webpack or Rollup to split your code into smaller chunks and load them on demand.
List Virtualization:
react-window or react-virtualized: Use libraries like react-window or react-virtualized to render only the visible portion of large lists, improving performance for long lists.
Key Coordination for List Rendering:
key prop: Always provide a unique key prop for each item in a list when using methods like map. This helps React identify items efficiently and optimize re-rendering.
Performance Profiling:
React DevTools Profiler: Use the Profiler in React DevTools to identify components that are causing performance bottlenecks and analyze their render times.
Other Techniques:
Avoid unnecessary state updates:
Update state only when necessary to prevent unnecessary re-renders.
Pure components:
Consider using pure components (React.PureComponent or React.memo) to optimize components that only render when props change.
Use shouldComponentUpdate:
In class components, use shouldComponentUpdate to manually control when a component should re-render.
Batch state updates:
If you're making multiple state updates, consider batching them together to avoid unnecessary re-renders.



- When do you use a functional component ?
In React, you should use a functional component when you need a simple, presentational component that doesn't require complex state management or lifecycle methods, prioritizing readability and ease of use;


- What are the some of the ways a render function can be triggered ?
A render function is typically triggered when there are changes to a component's state or props, 
meaning that any update to the values held within the state or received as props from a parent component 
will cause the render function to re-execute and update the UI accordingly; this is the primary mechanism in frameworks like React. 


- What are pure components ? why do you use them ?
Pure components in React are a specific type of component that optimizes performance by reducing the number of render operations in the application. 
They achieve this by implementing a shallow comparison of props and state within the component, to determine if the component should re-render.

- What happens behind the scenes when shouldComponentUpdate is triggered ?
When shouldComponentUpdate is triggered in a React component, it essentially performs a check to determine whether the component needs to re-render based on the upcoming changes to its props and state; 
if the comparison logic within the method decides a re-render is not necessary, 
it returns false, effectively preventing the component from updating in the DOM, thus optimizing performance by avoiding unnecessary re-renders.


- What are the differences between flux and redux ?
While both Flux and Redux are used for managing application state in front-end development, 
the key difference is that Flux is a design pattern focused on unidirectional data flow, 
while Redux is a concrete JavaScript library that implements the Flux architecture with a single store, 
enforcing immutability and using reducers to handle state updates, making it more structured and predictable than Flux which allows for multiple stores;
---
### Unit testing 
- What is your experience with unit testing ?

Unit testing is a type of testing where individual units or components of software are tested.
In the context of React applications, a unit could be a React component, a helper function, or any other JavaScript module. 
The goal is to verify that each unit of the software performs as designed.

- What all unit testing libraries you have used ?
Jest, Enzyme, React testing library.

---
### Javascript code exercise 
What is the output of below code snippet.

```javascript
var w  = 5;
(function(x){
  alert(w)
  alert(x)
  alert(z)
  alert(y)
  y = 0
  var z = 1
})()

```
ERROR!
5
undefined
undefined
/tmp/nc1tcQYKrl/main.js:9
  console.log(y)
              ^

ReferenceError: y is not defined
    at /tmp/nc1tcQYKrl/main.js:9:15
    at Object.<anonymous> (/tmp/nc1tcQYKrl/main.js:12:3)
    at Module._compile (node:internal/modules/cjs/loader:1565:14)
    at Object..js (node:internal/modules/cjs/loader:1708:10)
    at Module.load (node:internal/modules/cjs/loader:1318:32)
    at Function._load (node:internal/modules/cjs/loader:1128:12)
    at TracingChannel.traceSync (node:diagnostics_channel:322:14)
    at wrapModuleLoad (node:internal/modules/cjs/loader:219:24)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:170:5)
    at node:internal/main/run_main_module:36:49

Node.js v22.12.0

=== Code Exited With Errors ===

===========================================================

React component lifecycle has three categories – Mounting, Updating and Unmounting.
Mounting – Birth of your component
Update – Growth of your component
Unmount – Death of your component

React Component LifeCycle Hooks

        1. constructor
        2. componentWillMount()
        3. render()
        4. componentDidMount()
        5. componentWillReceiveProps()
        6. shouldComponentUpdate()

        // component kill methods

        7. componentWillUpdate()
        8. componentDidUpdate()
        9. componentWillUnmount()

Recently Added LifeCycle Hooks

Context API, useEffect, useState --- Newly added version by version

Explanation:

# Constructor()

        constructor will execute at booting time of component --constructor will execute only once
        Define state in constructor

# componentWillMount()

        componentWillMount() will execute after constructor
        componentWillMount() will execute only once
        in general we will do the initial modifications in state
        in general we will set global parameters like width, height

# render()

        after componentWillMount() automatically render() function will execute
        render() is mandatory lifecycle hook(main lifecycle hook)
        in general, we will place presentation logic in render()
        when ever change detected in state or props automatically this lifecycle hooks will execute

# componentDidMount()

        after render function immediately componentDidMount() life cycle hook will execute
        in general we will make asynchronous calls in ComponentWillMount()
        this is recommended state to change the state of component

# componentWillReceiveProps()

        when component will receive props from redux

# shouldComponentUpdate()

        if we want to update the state return "true" else "false"

# UNSAFE_componentWillUpdate()

        death method --> perform cleanup operations

# componentDidUpdate()

        if we integrate any third party UI elements
        plugin logic will write here

# componentWillUnmount()

        Before killing the component componentWillUnmount is executed.
        death method --> perform cleanup operations





