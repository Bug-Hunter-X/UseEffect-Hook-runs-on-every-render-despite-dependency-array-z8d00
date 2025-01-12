# React useEffect Hook Unexpected Behavior

This repository demonstrates an unusual issue with React's `useEffect` hook where the effect runs on every render, despite specifying a dependency array. The unexpected behavior is that the effect function still executes on every render, causing performance issues and potentially unexpected side effects.

The `bug.js` file contains the problematic code. The `bugSolution.js` file provides the corrected version.

## How to Reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.
5. Observe the console logs – they will be printed on each render.