### Arrays


#### 1. Basic examples

```js

// Intro to arrays - ordered collection of items 

// Declare the fruits array string
let fruits = ["apple", "mango", "grapes"];

// Declare the number's
let numbers = [1,2,3,4];

// Declare the mixed array
let mixed = [1,2,2.3, "string", null, undefined];
console.log("Mixed defined arrya is = ",mixed);
console.log("Number array is = ",numbers);
console.log("Index of the fruits is = ",fruits[2]);

// Declare the fruits array
let fts = ["apple", "mango", "grapes"];
let obj = {}; 
console.log(fts);

// Manipulate the fts index element
fts[1] = "banana";
console.log("Updated fruits array = ",fts);
console.log("Type of fts = ",typeof fts);
console.log("Type of Object = ",typeof obj);
console.log("Check if it's array = ",Array.isArray(fts));
console.log("Check if the object is array = ",Array.isArray(obj));

```




