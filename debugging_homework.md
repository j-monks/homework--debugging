# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?
A. It has the ability to pause the applications at a certain point in the code when it's running, in combination with the debugger. It helps determine where the error is coming from if it could possibly be coming from multiple sources

2. Does the line of code on a breakpoint run when you start debugging?
A. You have to test that indiviudal test, or while debugging it would just run through all the tests randomly and if it caught an error in another test, that you didn't have a breakpoint, it would never reach the one you are trying to debug. So you'd want to test that piece of code on its own.

3. How do we debug the next line of code?
A. You can do it by using some of the options available in the debugger, in the above options bar of the debugger console. By using the option 'step over' it will run the breakpoint line of the code then jump down to the next line and pause before running it.

4. What does the step into command do?
A. 'Step into' will switch into the actual method being invoked in its current break point and pause at the top of that method.

5. What is the difference between evaluate expression and evaluate code fragment?
A. Evaluate expression, allows you to run individual lines of java code, can run methods on instances of the objects we've created thus far. (doesn't need semi colon at end) 
Evaluate code fragment, allows you to run multiple lines of java code and you can use variables inside the code fragment enviroment. (does need semi colons at the end)
