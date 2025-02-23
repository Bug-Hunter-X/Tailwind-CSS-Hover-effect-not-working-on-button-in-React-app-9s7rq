# Tailwind CSS Hover effect not working on button in React app

This repository demonstrates a rare bug in Tailwind CSS where the hover effect does not work on a button in a React application. The issue might be caused by the interaction between Tailwind's utility classes and React's state management or other conflicting styles.

## Bug Description

The button does not change its background color on hover even though the `hover:bg-blue-700` class is applied. The count updates correctly, indicating that the click event is functional.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe that the button does not change color on hover.

## Solution

This issue is resolved in the `bugSolution.js` file.