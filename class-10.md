## Reading Day: 10
# Error Handling & Debugging
This chapter is about trial and error. I must admit
it was a bit comforting to read that javascript is hard
to understand and you'll make mistakes writing it.

## Order of Execution
To find the source of an error, it helps to know the order
in which statements are executed. Some tasks cannot complete until another statement or function has been run.
One of the many confusing things about javascript is the language does not neccessarily follow a logical path as statements
are processed. 

## Execution Contexts
As each function is written, new execution content follows. There are several different exectuion contexts: **Global Context and Variable Scope.** In Execution context, every statement in a script lives in one of three execution contexts. **(Glocal Context, Function Context, and Eval Context)** With Variable Scope, executuion contexts correspond the the notion of scope **(global or function level).**

## The Stack
This refers to how javascript processes one line of code at a time. When a statement needs data from another function, it stacks the neew function on top of the current task. The model provided in the book figurtively speaks 'Hurry up and wait'. Each time a script enters a new execution context, there are two phases of activity. 
1. Prepare - the new scope is created and the value of a keyword is determined.
1. Execute - Javascript assigns values to variables, references functions, runs code and executes statements

## Scope
Each execution context has its own variables object. It holds the variables, functions, and parameters available within it.

## Errors
Whenever the javascript interpreter comes across an error, it will look for error handling code. When an **Exception** is thrown, javascript stopts and checks the current execution context for exception-handling code. Say if an exception is found in a getName () function, the interpreter starts to look for error handling code in that function.

Error objects can help you find where your mistakes are and browsers have tools that help you pinpoint code errors. Getting to know the **Property Inspector** in Chrome has been 'eye opening' on the tools and information that are available to a developer. You can see a complete diagnostic of CSS, HTML, and Javascript.

**There are seven different types of error objects:**
- TypeError
- Range Error
- Syntax Error
- Reference Error
- Eval Error
- URIError

So when an error is found by the browser, there are ways that you can fix the problem.
To debug the script you must first track down the error. The Inspect Page is the gateway to this first step.
Debugging is about dedcution and eliminating potential causes of an error. The error message will tell you what the
relevant script  that caused the problem, line number where it became a problem, and the type of error.

Once you know the rough area in which the problem is located, you can then look at the line of code that is causing the error.

## Breakpoints
You can check stored values stored in variables. You can pause the execution of a script on any line using a Breakpoint.
If you set multiple breakpoints, you can step through them one-by-one to see where values chang and a problem might occur.
You can indicate a breakpoint should be triggered only if a condition you specify is met. 

## Common Errors
Common errors in writing code may include syntax errors like capitalizations, extra characters, or data type issues. My javascript experience so far has been learning the complexities of the syntax. 


[<== Back to Table of Contents](index.md)