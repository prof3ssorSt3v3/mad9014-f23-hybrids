## Numbers

1. Write a function, with one input argument, that uses `console.log` to output the argument value rounded to 2 decimal places, using `.toFixed()`. Eg: 2 becomes 2.00 and 3.456 becomes 3.46.
2. Write a function that accepts three arguments, each with a default value of zero. The function then uses `Math.min()` or `Math.max()` to determine which is the largest of the three. Then `return`
   the largest of the three numbers.
3. Write a function that accepts two arguments with default values of 1 and 10. The function creates a random **INTEGER** between the minimum and maximum values provided as arguments. The random
   integer needs to be inclusive, which means that if 2 and 5 were provided as the min and max then the random number could be 2, 3, 4, or 5. It includes the min and max values as possibilities. Use
   `Math.random()` wrapped in `Math.floor()` to generate the random integer. Remember that an integer has no decimal value. The general formula / algorithm for calculating a random number is
   `(random value * (max - min)) + min`.
4. Write a function that will create a random integer between 0 and 1000 and then convert the number to base 16 using the `toString()` method. The function should use `console.log` to output the new
   base-16 string.
