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



#### 2. Array method's


```js
// Array push,pop,shift,unshift 

// Declare the fruits array
let fruits = ["apple", "mango", "grapes"];

// O/p the array fruits
console.log("Output the array = ",fruits);

// Push is fast 
fruits.push("banana");
console.log("Updated array = ",fruits);

// Pop is fast
let poppedFruit = fruits.pop();
console.log("O/p the fruits = ",fruits);
console.log("Popped fruits is = ", poppedFruit);

// Unshift method will add elements at the beginning
fruits.unshift("banana");
fruits.unshift("myfruit");
console.log("By using the unshift method = ",fruits);

// Shift method will remove the elements from the end
let removedFruit = fruits.shift();
console.log("By using the shift method = ",fruits);
console.log("Removed fruit is = ", removedFruit);



```


#### 3. Primitive vs reference data types

```js
// Primitve vs reference data types

// Declare the varaible's
let num1 = 6;

// Assign the value of num1 to num2
let num2 = num1;

// O/p the 2 variable's
console.log("Value is num1 is = ", num1);
console.log("value is num2 is = ", num2);

// Ince the nums value
num1++;

// O/p the 2 variable's
console.log("*********After incrementing num1*********")
console.log("Value is num1 is = ", num1);
console.log("Value is num2 is = ", num2);

console.log("*********From here reference type array working*********")

// Declare the array 1
let array1 = ["item1", "item2"];

// Assign the array1 to array 2
let array2 = array1;

// O/p the array's
console.log("Array1 = ", array1);
console.log("Array2 = ", array2);

// Push the item3
array1.push("item3");

// O/p the ans
console.log("*********After pushing element to array 1*********");
console.log("Array1 = ", array1);
console.log("Array2 = ", array2);

```

#### 4. Ways to concatenate the array

```js
// How to clone array how to concatenate two arrays


// Declare the 2 array's
let array1 = ["item1", "item2"];
let array2 = ["item1", "item2"];

// O/p the 2 arrays
console.log("Array 1 = ",array1)
console.log("Array 2 = ",array2)

// Concatenate the array1 -slice(0) will start the ptr from 0 and goes till end
let aray2 = array1.slice(0).concat(["item3", "item4"]);
console.log("Method-1 Array 2 after Concatenate = ",aray2)

// Make the new array object
let ay2 = [].concat(array1,["item3", "item4"]);
console.log("Method-2 Array 2 after Concatenate = ",ay2)

// New way - spread operator most dev used this efficient way
let oneMoreArray = ["item3", "item4"]
let a2 = [...array1, ...oneMoreArray];
console.log("Method-3 Array 2 after Concatenate = ",a2)

// Comparision operator of both the arrays
console.log(array1===array2);

```














































