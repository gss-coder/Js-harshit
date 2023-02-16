### Conditional statement's

#### 1. If else condition

```js
// Example 1: If-else condition 

let age = 17;

if(age>=18)
{
	console.log("User can play ddlc");
}
else
{
	console.log("User can play mario");
}
```

```js
// Example 2: If-else condition 

let num = 13;

if(num%2===0)
{
    console.log("even");
}

else
{
    console.log("odd");
}
```

```js
// Example 3: True false values
// falsy values false,"",null,undefined,0,truthy ,"abc",1, -1

let firstName= 0;
if(firstName)
{
    console.log(firstName);
}

else
{
    console.log("firstName is kinda empty");
}
```


```js


// Example 3 - And & or operator 


if(firstName[0] === "H")
{
     console.log("your name starts with H")
}

if(age > 18)
{
    console.log("you are above 18");
}

if(firstName[0] === "H" && age>18)
{
    console.log("Name starts with H and above 18");
}

else
{
    console.log("inside else");
}


let firstName = "arshit";
let age = 16;

if(firstName[0] === "H" || age>18)
{
    console.log("inside if");
}

else
{
    console.log("inside else");
}

```


#### 2. Ternary operator


```js

// Ternary operator 

// Declare the required variable's
let age = 4;
let drink;

// If else case
if(age>=5)
{
   drink = "coffee";
}
else
{
   drink = "milk";
}

// O/p the drink variable
console.log(drink);
```


```js
// Ternary operator / conditional operator 

let age = 3;
let drink = age >= 5 ? "coffee" : "milk";
console.log(drink);


```


#### 3. Guess the number

```js

// Nested if else
// winning number 19 
// 19 your guess is right, 17 too low , 20 too high 

// Declare the variabl'e
let winningNumber = 19;
let userGuess = +prompt("Guess a number");

// If case
if(userGuess === winningNumber)
{
    console.log("Your guess is right!!");
}

// Else case
else
{
    // If case
    if(userGuess < winningNumber)
    {
        console.log("too low !!!");
    }
    
    // Else case
    else
    {
        console.log("too high !!!");
    }
}

```


#### 4. Switch statement

```js

// Declare the day variable
let day = 9;

// Use the switch statement
switch(day)
{
    case 0:
        console.log("Sunday");
        break; 
    case 1:
        console.log("Monday");
        break;
    case 2:
        console.log("Tuesday");
        break;
    case 3:
        console.log("Wednesday");
        break;
    case 4:
        console.log("Thrusday");
        break;
    case 5:
        console.log("Friday");
        break;
    case 6:
        console.log("Saturday");
        break;
    default:
        console.log("Invalid Day");
}

```






	














