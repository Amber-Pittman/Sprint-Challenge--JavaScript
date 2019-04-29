## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

The biggest difference between `.forEach()` and `.map()` is that map returns a new array of elements while in turn, passing each element back to the callback.

2. What is the difference between a function and a method?

A function is independent of other code blocks (although they can be nested). Methods, on the otherhand are dependent placed inside other code blocks, like you see in Classes. 

3. What is closure?
Closures allow us to access values in scope that have already been invoked (lexical scope).

4. Describe the four rules of the 'this' keyword.
    A. When in the global scope, the value of `this` will be the Window object.
    B. Whenever a function is called by a preceding dot, the object to the left of the dot gets `this`.
    C. Whenever a constructor function is used, `this` refers to the specific instance of the object that is created and returned by the constructor function.
    D. Whenever JavaScript's `.call()` or `.apply()` method is used, `this` is explicity defined.

5. Why do we need super() in an extended class?

In extended classes, `super()` takes care of the binding with a `.call()`. Furthermore, `super()` grants access to the "parent" class (inheritance). It only works when `extends` is used in the "child" class. 

For example, the Dog class can utilize a method from an Animal class, as long as both `extends` and `super()` are in the syntax.