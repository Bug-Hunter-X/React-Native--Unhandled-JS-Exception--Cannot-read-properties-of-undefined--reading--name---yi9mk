# React Native Unhandled JS Exception: Cannot read properties of undefined (reading 'name')

This repository demonstrates a common React Native bug and its solution. The bug occurs when attempting to access a state variable or prop before it has been assigned a value, often due to asynchronous operations not completing before rendering.

## Bug
The `bug.js` file contains code that fetches data and attempts to display it before the data has been fetched. This results in a runtime error because the application attempts to access a property of `undefined`.

## Solution
The `bugSolution.js` file demonstrates how to solve this issue using conditional rendering.  It checks if the data has been fetched before attempting to render it. This prevents runtime errors and provides a better user experience.