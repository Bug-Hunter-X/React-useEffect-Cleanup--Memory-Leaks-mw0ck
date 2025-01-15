# React useEffect Cleanup: Memory Leaks

This example demonstrates a common error in React's `useEffect` hook where a missing return statement in the cleanup function can cause memory leaks. The unmounted component's `fetch` request continues running. The solution demonstrates the proper use of a cleanup function.