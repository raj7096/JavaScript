# JavaScript

## What is JavaScript?

JavaScript is the programming language of the Web.

## How to include Javascript in Html Documents

* Using <script></script> Tag.

## Declare variable In JavaScript
 
* Using let,var,const
let x=1
var y=2
const z=3

## difference between let var and const
* const is use declare constant variable.let is use to declare variable but we can change it latter. while there is problem in var it is accessible outside of it scope. 

## Datatype in JavaScript
* number - eg 1
* string - eg "raj"
* Boolean - True or False
* Null - Empty
* Undefined - When Value Is Not Defined
* Array - It is collection of elements of same type
* Object - Instance of class

## Javascript functions
* it is a block of code which can be access by its name
 eg ```function xyz(){
        console.log("Hello World");
}```
* We Can Call function By Its Name
eg ```xyz()```

## Array - It is collection of elements of same type
* how to declare array - ```a[3] = [1,2,3];```
* we can access array by index. eg - a[0] it will return 1.

## Class And Object
* class is blueprint of Object eg car
* Object is Instance of class(Real World Entity)
```   
         class xyz{} 
         const a = new Object();
 ```
## Operators
* +,-,*,**,<,>,/,% 

## JavaScript Loops
* For,while,do while,switch
* For,switch,While Loops Are entry control Loop And Do While Loop is exit Control Loop

## Conditional Statement
* if else,else if loops 
* ? : (ternary operator)

## Use Of **use strict**
* it run javascript in strict mode
```
    x=10;
    console.log(x);
```
this code will generate error because x is not declared before its initailzation.

## alert, prompt, confirm
* alert - It Will Display Message in PopUp
* prompt - shows a message asking the user to input text. It returns the text or, if Cancel button or Esc is clicked, null
* confirm - shows a message and waits for the user to press “OK” or “Cancel”. It returns true for OK and false for Cancel/Esc.
```
    alert("Hello");
    result = prompt(title, [default]);
    console.log(result)
    let isBoss = confirm("Are you the boss?");
    alert( isBoss ); 
```
## Equality operators: == and !=
* he equal-to operator (==) returns true if both operands have the same value; otherwise, it returns false. 
* The not-equal-to operator (!=) returns true if the operands don't have the same value; otherwise, it returns false.

## Difference Between == and ===
* == will check only value not the data type.
* === will check value as well as Data type.

## Primitive Values & Object
* Data types that are known as primitive values in JavaScript are numbers, strings, booleans, null, undefined. Objects such as functions and arrays are referred to as non-primitive values.
* The fundamental difference between primitives and non-primitives is that primitives are immutable and non-primitives are mutable.
        
