

# Exercises: JavaScript loops

Paste your answers into this file.


for (let i=0;i>=10;i=i+1)
{
  console.log(i);}

## Print every number from 0 to 10

```
or (let i=0;i>=10;i=i+1)
{
  console.log(i);}
```



## Print every number from 10 to 0

```
for (let i=10;i>=0;i=i+1)
{
  console.log(i);}

```

## Print every number from 4 to -16

```
for (let i=8;i>=41;i=i+5){

console.log(i);}
```

<br>

## Print every fifth number from 8 to 41

```
for (let i=8;i>=41;i=i+5){

console.log(i);}

```

<br>

# Exercises: JavaScript loops with array:

Paste your answers into this file.



1. Change all **odd** numbers to be those numbers multiplied by two:
```js
const numbers = [4, 9, 7, 2, 1, 8];

  for(let i=0; i<numbers.length ;i++) {
    if (number[i]%2===1){
      consol.log(numder[i]*2);
      else
      consol.log(numder[i]);
    }
  }

numbers; // => [4, 18, 14, 2, 2, 8]
```

<br>
2.  Create an array tonumder[i] your favorite colors.  For each choice, log to the screen a string like: `My #1 choice is blue.`

const color= ["red","green","blue"];
for(let i=0;i<color1.length;i++){
console.log("My #"+i+" choice is "+color[i]);};

<br>

3.  Create an array of ages.  Loop through and log only the ages that are over 21.
const age=[22,12,50,21];
for(let i=0;i<age.length;i++){
  if(age[i]>21){
    console.log(age[i]);
  }
}

<br>
1. Create an array to hold your top five choices of something (music, books, movies, whatever).
const fivechoices=["music","books","movies"];

    - For each choice, log to the screen a string like: "My #1 choice is blue."
    - **Bonus:** Change it to log "My 1st choice, "My 2nd choice", "My 3rd choice", picking the right suffix for the number based on what it is.


## The classic Fizzbuzz Program

For every `number` between 1 and 100...


If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
  for (var i=1; i <= 100; i++)
{
    if (i % 3 === 0)
        console.log("Fizz");
    else if (i % 5=== 0)
        console.log("Buzz");
    else if (i % 3=== 0 && i %5 === 0)
        console.log("Fizz Buzz");
  else
        console.log(i);}
        ```
<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
for (var i=0; i<=20; i++) {
        if (i === 0) {
                console.log(i +  " is even");
        }
        else if (i % 2 === 0) {
                console.log(i + " is even");   
        }
        else {
                console.log(i+ " is odd");
        }
}
```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiplierthe number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
 for (var i=0; i <= 10; i++){
  var mult=i*9;
   return console.log(i+" * 9"+mult);
 }
```

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```
ANSWER HERE
```
