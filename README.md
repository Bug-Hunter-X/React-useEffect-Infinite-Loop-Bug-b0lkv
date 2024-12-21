# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React's `useEffect` hook: creating an infinite render loop by omitting necessary dependencies.  The `bug.js` file contains the buggy code, while `bugSolution.js` provides the corrected version.

## Bug Description
The `useEffect` hook, without the correct dependency array, causes the component to re-render continuously. This leads to performance issues and potential crashes. The `console.log` statements help visualize the infinite loop.