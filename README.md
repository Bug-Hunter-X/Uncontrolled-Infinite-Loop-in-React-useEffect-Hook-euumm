# Uncontrolled Infinite Loop in React useEffect Hook

This repository demonstrates a common error in React applications involving the `useEffect` hook.  The example shows an infinite render loop caused by omitting the dependency array in `useEffect`, resulting in the effect running after every render, leading to an uncontrolled update cycle.

The solution provided corrects this issue by including the appropriate dependencies in the dependency array, allowing the effect to run only when necessary.