# Expo CLI Error: Managed vs. Bare Workflow Module Mismatch

This repository demonstrates a common error encountered when mixing Expo's managed and bare workflows.  Attempting to use modules designed for one workflow within the other leads to module resolution failures during the build process. 

The `expoBareError.js` file contains code that will trigger the error in a bare workflow environment. The `expoBareSolution.js` file provides a corrected version, showing how to adapt the code for a consistent workflow.  Please refer to the Expo documentation for best practices on managing dependencies and workflows.

## How to Reproduce

1. Clone this repository.
2. Navigate to the directory in your terminal.
3.  Try running the `expoBareError.js` file in an Expo bare workflow project (Make sure you have the necessary dependencies installed). You should encounter a module resolution error. 
4. Then run the `expoBareSolution.js` file which contains the solution for the error.

## Solution

The solution involves ensuring consistency in your workflow and carefully managing dependencies to prevent this error.  See `expoBareSolution.js` for an example of resolving the incompatibility.