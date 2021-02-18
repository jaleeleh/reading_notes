 # Ch: 10 “Error Handling & Debugging”
  * ORDER OF EXECUTION:To find the source of an error, it helps to know how scripts are processed.The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

  * The JavaScript interpreter uses the concept of execution contexts.
  There is one global execution context; plus, each function creates a new
  new execution context. They correspond to variable scope.

  * Debugging is about deduction: eliminating potential causes of an error.

  * The JavaScript console will tell you when there is a problem with a script,where to look for the problem, and what kind of issue it seems to be.
  
  * When you have set breakpoints,you will see that the debugger
  lets you step through the codeline by line and see the values
   or variables as your scriptprogresses.
  