## TDD Pros
- forces developer to think about requirements before writing code
- encourages writing code that is modular and follows the single responsibility rule
- quickly detects errors caused by mistakes such as typos, forgetting to import package, etc...
- makes it quick to test old code for regression
- makes it easy for others (developers, stakeholders) to understand what your code does

## TDD Cons
- increases amount of time it takes to write each function
- makes the code base larger
- might have to refactor tests each time a piece of code is refactored
- can require complicated setup (e.g. fixtures) for modules which dependend on other modules to functions
