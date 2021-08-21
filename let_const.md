Quiz
- What is the difference between var and let?

In the global space, var can be attached to the window object. "let" cannot. 
Var will also hoist to the top of the scope it's defined in.
Like "let" you can redclare and reassign var variables. 

"let" is block-scoped. So it only works between the curly brackets of a non-object-literal. It can be reassigned but not redclared. 


- What is the difference between var and const?
"const" can't be redeclared or reassigned. It's also block scope. 

- What is the difference between let and const?
"let" can be redeclared and reassigned while const can't. 
- What is hoisting?
The browser will "move" the variable to the top of the scope it's defined in. 
