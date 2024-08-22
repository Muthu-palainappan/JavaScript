# JavaScript
 Whether you’re a beginner looking to understand the fundamentals or an experienced developer aiming to refresh your knowledge, this tutorial covers everything you need to know.

# Variables
In JavaScript, variables are used to store and manage data. They are created using the var, let, or const keyword.

1. var Keyword
The var keyword is used to declare a variable. It has a function-scoped or globally-scoped behavior.

var x = 10;
Example: In this example, we will declare variables using var.


var a = "Hello Geeks"
var b = 10;
var c = 12;
var d = b + c;

console.log(a);
console.log(b);
console.log(c);
console.log(d);

Output
Hello Geeks
10
12
22
2. let Keyword
The let keyword is a block-scoped variables. It’s commonly used for variables that may change their value.

let y = "Hello";
Example: In this example, we will declare variables using let.


let a = "Hello learners"
let b = "joining";
let c = " 12";
let d = b + c;

console.log(a);
console.log(b);
console.log(c);
console.log(d);

Output
Hello learners
joining
 12
joining 12
const Keyword
The const keyword declares variables that cannot be reassigned. It’s block-scoped as well.

const PI = 3.14;
Example: In this example, we will declare the variable using the const keyword.


const a = "Hello learners"
console.log(a);

const b = 400;
console.log(b);

const c = "12";
console.log(c);
// Can not change a value for a constant
// c = "new"
// console.log(c) will show error

Output
Hello learners
400
12
Data Types
JavaScript is a dynamically typed (also called loosely typed) scripting language. In JavaScript, variables can receive different data types over time. The latest ECMAScript standard defines eight data types Out of which seven data types are Primitive (predefined) and one complex or Non-Primitive.

# Primitive Data Types
The predefined data types provided by JavaScript language are known as primitive data types. Primitive data types are also known as in-built data types.

Number: JavaScript numbers are always stored in double-precision 64-bit binary format IEEE 754. Unlike other programming languages, you don’t need int, float, etc to declare different numeric values.
String: JavaScript Strings are similar to sentences. They are made up of a list of characters, which is essentially just an “array of characters, like “Hello GeeksforGeeks” etc.
Boolean: Represent a logical entity and can have two values: true or false.
Null: This type has only one value that is null.
Undefined: A variable that has not been assigned a value is undefined.
Symbol: Symbols return unique identifiers that can be used to add unique property keys to an object that won’t collide with keys of any other code that might add to the object.
BigInt: BigInt is a built-in object in JavaScript that provides a way to represent whole numbers larger than 2^53-1.
Non-Primitive Data Types
The data types that are derived from primitive data types of the JavaScript language are known as non-primitive data types. It is also known as derived data types or reference data types.

Object: It is the most important data type and forms the building blocks for modern JavaScript. We will learn about these data types in detail in further articles.

