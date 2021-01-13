Read10

The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope. 

Variables declared inside fuctions connot be used outside the functions 
When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.

If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code.

Debugging is about deduction: eliminating potential causes of an error. 

There are several uses for the console . log () method:
1. The first line is used to indicate the script is running.
2. Next an event handler waits for the user leaving a text input,
and logs the value that they entered into that form field

If you want to write a set of related data to the console, you can use the console. group () method to group the messagestogether. You can then expand and contract the results

Using the console. assert() method, you can test if a condition is met

debugger; >> A breakpoint is set i f the devel oper tools are open 

To create your own error, you use the following line: throw new Error( 1
message 1 ) ;


JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.

If you know that you may get an error, you can handleit gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 