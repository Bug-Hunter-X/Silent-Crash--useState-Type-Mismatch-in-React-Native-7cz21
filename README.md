# Silent Crash: useState Type Mismatch in React Native

This repository demonstrates a subtle but frustrating bug in React Native involving the `useState` hook.  When the type of the value used to update state does not match the initial state type, the application crashes silently without any clear error messages in the console. This makes debugging significantly harder.

The `bug.js` file contains the problematic code.  The `bugSolution.js` provides a solution and explanation.

## How to Reproduce

1. Clone this repository.
2. Run the app in a React Native environment (e.g., using Expo).
3. Observe that the app crashes without any obvious error messages when the button is pressed.

## Solution

The solution involves careful type checking and handling of potential type mismatches before updating state. See `bugSolution.js` for implementation details.