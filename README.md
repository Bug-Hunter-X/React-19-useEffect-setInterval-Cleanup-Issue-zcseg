# React 19 useEffect setInterval Cleanup Issue

This repository demonstrates a common error when using `setInterval` within a `useEffect` hook in React 19. Forgetting to clear the interval in the cleanup function can lead to memory leaks and unexpected behavior.

The `bug.js` file contains the problematic code, while `bugSolution.js` provides the corrected version.  This illustrates the importance of properly cleaning up intervals to prevent resource exhaustion.