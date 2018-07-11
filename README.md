# Callbacks
Understanding Callbacks in ES6

What is a callback commomly known as a higher-order function? A callback is a function to be executed after another function is executed. 
That is a pretty limited description. Let me go into further detail, so you can get a good understanding on what callback is. 

In JavaScript, functions are first-class objects; that is, functions are of the type Object and they can be used in a first-class manner like any other object (String, Array, Number, etc.) since they are objects themselves. They can be stored in variables, passed as arguments to functions, created within functions, and returned from functions.

Within functions are the first-class objects, we can pass a function as an argument in another function and later execute that passed-in function or even return it to be executed later. This is the essence of using callback functions in JavaScript. Callback functions are the most widely used functional programming technique in JavaScript, and you can find them in just about every piece of JavaScript. 

We can pass functions around like variables and return them in functions and use them in other functions. When we pass a callback function as an argument to another function, we are only passing the function definition. We are not executing the function in the parameter. In other words, we aren’t passing the function with the trailing pair of executing parenthesis () like we do when we are executing a function.

And since the containing function has the callback function in its parameter as a function definition, it can execute the callback anytime.

Note that the callback function is not executed immediately. It is “called back” (hence the name) at some specified point inside the containing function’s body

