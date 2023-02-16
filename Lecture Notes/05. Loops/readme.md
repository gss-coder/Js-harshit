### Loops 

#### 1. While loop
// While loop - [0-9]

```js
// While loop till 9 
while(i<=9)
{
    // Log the o/p
    console.log(i);
    
    // Incr the counter
    i++;
}

// O/p the ans
console.log(`current value of i is ${i}`);
console.log("hello");
```

#### 2. For loop

```js
// Example 1
// Intro to for loop 
// Iterate on the loop

for(let i = 0;i<=9;i++)
{
    console.log(i);
}

// O/p the ans
console.log("value of i is ",i);

```


```js
// Example 2

// Declare the vars
let total = 0;
let num = 100;

// Iterate on the loop
for(let i = 1; i<=num; i++)
{
    total = total + i;
}

// O/p the ans
console.log(total);

```


#### 3. Break and continue keyword


```js


// Break keyword
for(let i = 1; i<=10; i++)
{
    if(i===4)
    {
        break;
    }
    console.log(i);
}

console.log("*******************")

// Continue keyword
for(let i = 1; i<=10; i++)
{
    // If ith value is equal to 4 then skip the iteration
    if(i===4) continue;
    
    // Log the o/p
    console.log(i);
}

```


#### 4. Do while loop

```js

// Do while loop

// Assign the value of the ith variable
let i=1

// Loop till the condition fails
while(i<=9)
{
    // O/p the ans
    console.log(i);
    
    // Incr the value of i
    i++;
}

console.log("**********************")

// Use the do while loop
do{
    
    // O/p the ans
    console.log(i);
    
    // Ince the ith value
    i++;
}while(i<=19);


// O.p the value of i
console.log("value of i is ", i);


```
























