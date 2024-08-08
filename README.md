https://github.com/DanielG79/ALAB-320H.9.1---Building-a-Todo-List.git

ALAB 320H.9.1 - Building a Todo List

Learning Objectives
After completing this lab, learners will have demonstrated the ability to:

Use the useReducer and/or useImmerReducer hook to manage state with reducer functions.
Use useState in places where reducers are not appropriate or necessary.
Implement controlled forms and inputs.
Effectively decide where pieces of state should live.
Use conditional rendering and conditional styling to provide a positive, interactive user experience.
Create a complete React application from a set of desired functionality.

 CodeSandbox
This lab uses CodeSandbox as one of its tools.

If you are unfamiliar with CodeSandbox, or need a refresher, please visit our reference page on CodeSandbox for instructions on:

Creating an Account
Making a Sandbox
Navigating your Sandbox
Submitting a link to your Sandbox to Canvas

Instructions
This lab will test your ability to build an application from scratch, using a set of desired functionality to drive your design decisions.

Create a React CodeSandbox and name it "React Todo List."
Follow the requirements below to create your React application.
Submit the link to your CodeSandbox on Canvas when you are finished.
The layout and styling of the application is left up to your discretion. There are no layout or styling requirements, but you should always make sure your applications are neat, sensible, and provide a good user experience. If you are left with extra time, there is always more styling to be done!


Deliverables
A link to a CodeSandbox that contains your completed lab with no errors (comment things out if they do not work).

Requirements
After reading through the requirements below, it is recommended you start with a mockup and follow the steps described in "Thinking in React" to complete your application. Remember, stay organized!

Your todo list application must have:

A heading labeling it as a "todo list."
A list of "todo" items, which are strings listing activities to be accomplished (e.g. "find that missing sock"). Each "todo" item should have:

A checkbox next to it which indicates whether it is "complete."
A "delete" button next to it which removes it from the list.

The "delete" button should be disabled unless the todo is complete!
An "edit" button that replaces the todo string with a text input used to edit the todo.

Hint: bind the value of this text input to a piece of state so that it is always accurate, even when first displayed!
When this text input is active, the "delete" and "edit" buttons should be hidden, and a "save" button should appear. The "save" button should save any changes made to the todo within the text input.
An input element that creates new todo items and adds them to the list.
New todos should be added to the top of the list visually; the oldest todos should be at the bottom.
