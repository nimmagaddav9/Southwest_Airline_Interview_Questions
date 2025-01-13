# Southwest_Airline_Interview_Questions

Features build? 

Vijay Nimmagadda here, Austin, Texas.
I am a core UI Developer with 10+ years of experience building .com websites for different organizations using HTML5, CSS3, JavaScript, React.js, and Redux. 

In the past 2 years, I worked on the React migration team, where I converted the .net pages to react on united.com. 
Frontend is React, backend is Java and used ATMOS library for CSS styling.
Worked on Forgot password, Forgot MileagePlus number, security questions, Sign-in features, Miles-Pooling, United Club pass,  Recent Activity, dashboard updates and KTN(Known Traveler Number), 
Accessibility guidelines features on united.com.
used middleware such as redux-saga to handle asynchronous tasks such as API calls, data fetching, and impure actions in a more organized and efficient way.
The new initiative worked on Miles-Pooling( points you get after traveling), TSA Precheck, Account security and management features, and Under18.

Previously worked with Accelerator team for Visa Inc. remediation of MBDA modules like Application Management, Account Management, Portfolio Management, Analytics, Recurring billing, Virtual Terminal, etc for bank users like Wells Fargo,  Bank of America, etc

Capital Group worked on DAVIS Project. Davis stands for Data visualization where we build different highcharts using react and integrate into the AEM., the backend is Java. Previously I worked on Creative Workbench, a writing tool where articles are published on capital group websites.

At Cerner Corporation worked on the medical examination forms.

In Office Depot worked on black Friday reporting.

Satinos Technologies created a tax portal and a schoomin website for the Vignan schools.
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
It is a recent project. lot of times we have to deal with legacy code. we have to use functional components.


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

Redux is a predictable state container for JavaScript applications. It helps to you write applications, run in different environments and easy to test. And simply we called as Redux is a state management tool.
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





