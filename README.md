# Expo Managed Workflow Limitation Error

This repository demonstrates a common error encountered when developing with Expo's managed workflow: attempting to use native modules or functionalities that are not directly supported.

The `bug.js` file shows code that attempts to use such unsupported feature, leading to a generic Javascript error.

The `bugSolution.js` file demonstrates solutions to avoid this error by either using an Expo-compatible alternative, switching to the bare workflow or using a different approach altogether that doesn't involve unsupported features. 

## Steps to Reproduce
1. Clone the repository.
2. Run `npm install`.
3. Attempt to run the `bug.js` example using Expo CLI. Observe the error.
4. Run the `bugSolution.js` example. This solution provides a workaround avoiding the error.