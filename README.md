![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)

JavaScript Warm-Up: Stack
=========================

> In computer science, a stack or LIFO (last in, first out) is an abstract data type that serves as a collection of elements, with two principal operations: push, which adds an element to the collection, and pop, which removes the last element that was added. -- [Stack (abstract data type), Wikipedia](https://en.wikipedia.org/wiki/Stack_\(abstract_data_type\))

Instructions
------------

1. [Fork and clone](https://github.com/ga-wdi-boston/meta/wiki/ForkAndClone) this repository.
1. Change into the new directory.
1. Follow the remaining instructions.

Create a custom JavaScript object modeling the stack using a constructor function and a prototype. Starter code has been provided for you in [`lib/stack.js`](lib/stack.js).

Requirements
------------

* You should be able to create a new stack with `var stack = Stack.new();`.
* Your stack should have two methods, `push` and `pop`.
    * `push` adds a new value to the stack's storage and returns the added value
    * `pop` removes the most recently added value from the stack's storage and returns it
* You should not use `Array.prototype.push()` or `Array.prototype.pop()`

Bonus
-----

Pre-fill the stack on instantiation.

```
var stack = Stack.new([1,2,3])
stack.pop() //=> 3
```

Which parts of each method are side-effects, and which are the "main" effect?

[License](LICENSE)
------------------

Source code distributed under the MIT license. Text and other assets copyright
General Assembly, Inc., all rights reserved.
