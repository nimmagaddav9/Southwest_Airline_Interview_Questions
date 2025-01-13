# Southwest_Airline_Interview_Questions

Features build? 
In the past 2 years, I worked on the React migration team, where I converted the .net pages to react. 
Frontend is React, backend is Java and used ATMOS library for CSS styling.
Worked on Forgot password, Forgot MileagePlus number, security questions, Sign-in features, Miles-Pooling, United Club pass,  Recent Activity, dashboard updates and KTN(Known Traveler Number), Accessibility guidelines features on united.com.
used middleware such as redux-saga to handle asynchronous tasks such as API calls, data fetching, and impure actions in a more organized and efficient way.
The new initiative worked on Miles-Pooling( points you get after traveling), TSA Precheck, Account security and management features, and Under18.

Challenges? 
Initially worked on Sign-in features where account gets locked if you answer 2 questions wrong. Then account is hard locked.
I need to request a backend developer to unlock it. I have created a list of steps needed to unlock and account where it has bunch of calls within postman and made it simple.

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
it depends on the project. if project doesn't have complicated state i would choose functional components. really like hooks.
if there is complicated logic then i will pick react class components. 
if want to redux then class components.
mixing and matching, simplier components, functional components.

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
