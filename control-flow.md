## Control Flow

1. Take the code below and add two `if` statements around the two `console.log` statements, so that the first console command only runs if the value of `id` is greater than 5 and the second console
   command only runs if the value of `id` is NOT equal to 17.

```js
let id = 15;

console.log('The value of id is greater than 5.');

console.log('The value of id is NOT 17.');
```

2. Convert the following code into a single line with a `ternary` statement that assigns it's result to the variable `isTony.

```js
let isTony;
let name = 'Bob';
if (name == 'Tony') {
  isTony = true;
} else {
  isTony = false;
}

// let isTony = ...
```

3. Write a multiline comment with the list of all the possible `falsey` values in JavaScript.
4. Write a `for loop` that will `console.log` only the numbers from 25 to 5 in descending order. Eg: `25, 24, 23, 22, 21,...7, 6, 5`. Do not use an `Array` to accomplish this. The output values should
   be only the value of your counter variable.
