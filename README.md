# React setInterval useEffect Memory Leak
This repository demonstrates a common mistake in React: using setInterval within useEffect without proper cleanup. This leads to a memory leak because the interval continues to run even after the component is unmounted.

The `bug.js` file shows the faulty implementation. The `bugSolution.js` file provides the corrected version.