This repository demonstrates a common yet subtle bug in TypeScript related to optional properties. The `bug.ts` file contains code that will produce a runtime error if the input object doesn't contain the expected property. The `bugSolution.ts` file shows how to properly handle optional properties using optional chaining or the nullish coalescing operator.