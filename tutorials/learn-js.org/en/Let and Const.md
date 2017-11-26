Tutorial
--------

ECMAScript 6, also known as ECMAScript 2015, is the latest significant update to Javascript. While the . Subsequent updates to the language have been released, but they do not have ES6's breadth of useful features, nor have they been as widely adopted as ES6

ES6 

Two s

The `let` keyword functions similar to the `var` keyword; it can define any type of variable that 'var', and can be redfined just as you would with  



Like almost every dynamic language, JavaScript is a "duck-typed" language, and therefore every variable is defined using the `var` keyword, and can contain all types of variables. 

We can define several types of variables to use in our code:

    let myNumber = 3;                   // a number
    let myString = "Hello, World!"      // a string
    let myBoolean = true;               // a boolean

Just as with the `var` keyword, variables defined


One subtle, key difference - var is scoped lexically - it scopes to the nearest function block. The  'let' keyword is block-scoped; it's scope by the first eclosing set of curly brackets. These brackets could be a function, but they could by several other 

The const keyword it cannot be redfined; the following code will throw an error


A few notes about variable types in JavaScript:

* In JavaScript, the Number type can be both a floating point number and an integer. 
* Boolean variables can only be equal to either `true` or `false`.

There are two more advanced types in JavaScript. An array, and an object. We will get to them in more advanced tutorials.

    var myArray = [];                    // an array
    var myObject = {};                  // an object

On top of that, there are two special types called `undefined` and `null`.

When a variable is used without first defining a value for it, it is equal to undefined. For example:

    var newVariable;
    console.log(newVariable); //prints undefined

However, the `null` value is a different type of value, and is used when a variable should be marked as empty. `undefined` can be used for this purpose, but it should not be used.

    var emptyVariable = null;
    console.log(emptyVariable);


will print out `null`

Exercise
--------

You must define the following variables:

1. A number called myNumber which contains the number `4`;
2. A string called myString which contains the sentence `Variables are great.`;
3. A boolean called myBoolean which contains the value `false`;

Tutorial Code
-------------

console.log("myNumber is equal to " + myNumber);
console.log("myString is equal to " + myString);
console.log("myBoolean is equal to " + myBoolean);

Expected Output
---------------

myNumber is equal to 4
myString is equal to Variables are great.
myBoolean is equal to false

Solution
--------
var myNumber=4;
var myString="Variables are great.";
var myBoolean=false;
console.log("myNumber is equal to " + myNumber);
console.log("myString is equal to " + myString);
console.log("myBoolean is equal to " + myBoolean);
