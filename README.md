### 1. What is the difference between var, let, and const?
**var:** var works anywhere in the function, even before you declear but it give you undefined, you can reassign in var.
**let:** let only works inside the block where you declear it (like-if, for loop), if you access let befor initialize let give you error by (Temporal Dead Zone), you can reassign in let.
**const:** const only works inside the block where you declear it (like-if, for loop), if you access const befor initialize const give you error same as let but you can't reassign in const.

### 2. What is the difference between map(), forEach(), and filter()?
**map:** map operates on all item and returns a new array but the original array is not changed.
**forEach:** forEach Operates on all item like a loop but does not return anything.
**filter:** filter Checks every item returns a new array with only items that match your condition.

### 3. What are arrow functions in ES6?
arrow function is a shorter way to write functions in JavaScript, where you can work without writing the function keyword. Arrow functions do not have their own this. they use the this from their parent scope. 

### 4. How does destructuring assignment work in ES6?
Destructuring is a shortcut method where you can separate values ​​from within an array or object and assign them to variable.
**Array Destructuring:**
  Variables are declared within square brackets [] on the left-hand side of the assignment operator.
  The values are extracted from an array on the right-hand side based on their position (index).

### 5. Explain template literals in ES6. How are they different from string concatenation?
Template Literals is new and easier way to write strings in JavaScript. They are written using backtick (`), write multi-line strings easily and it allow you to Place variables or expressions inside a string like-${variableName}.

template literals different from string concatenation 
1 Variable insertion template literals uses ${} and string concatenation uses +
2 Multiline strings template literals directly write on new lines and string concatenation \n +
