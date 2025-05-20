Min Aung Paing

Fill your answer in your README.md
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

I choose Within a Github action that runs whenever code is pushed 

Integrating automated tests within a GitHub Action that runs on every code push make sure continuous integration and early bug detection. This approach prevents broken code from being merged into the main branch by automatically validating new changes especially when working with multiple contributors, and allows developers to identify and fix issues immediately rather than waiting until the end of the development cycle.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No. End-to-end tests are designed to test the entire application flow from user input to final output in a real or simulated browser environment. If you're only checking whether a function returns the correct output, that is better suited for a unit test, which isolates the function and verifies its behavior in a controlled context.


