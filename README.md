# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React's `useEffect` hook: an infinite loop caused by an incorrect dependency array.

## Bug Description
The `useEffect` hook in `bug.js` has an incorrect dependency array.  It's missing the `count` variable resulting in infinite re-renders.

## How to Reproduce
1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Observe the console output showing the infinite loop.

## Solution
The `bugSolution.js` file provides a solution by correctly adding `count` as a dependency to the `useEffect` hook.