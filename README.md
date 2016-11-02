Problem Set Zero
================



Directions
----------

Create a class named *ProblemSet0* which contains methods that solve the questions below. Also submit a test class, *Tests0*, with a main method that tests your Problem Set. Please include at least 3 test cases for each problem. While it isn't graded, it will benefit you to carefully test your edge cases.

Grading
-------
| Category | Points |
| --- | --- |
| Documentation | 2 |
| Functionality | 17 |
| Tests | 1 |

| Deduction | Points |
| --- | --- |
| Not calling sumDigits from isDivisibleBy3 | 1 |


Problems
--------
0. Take a few minutes and refresh yourself on how binary numbers work and how you would convert a decimal (base-10) number to binary (base-2). Now create a method named toBinary that will take in an int parameter and return a String that contains the binary digits representing the int. (Note - why can we not simply return an int? How would that limit us?)

1. Write a method named rollDie that takes a positive int n and returns the result of rolling a fair die with n sides on it.

2. Write a method named multiples that takes in the number of rows as a parameter and prints a “Multiple Table.” For example, multiples(7) would produce:

<pre>
1
2    4
3    6    9
4    8    12    16
5    10    15    20    25
6    12    18    24    30    36
7    14    21    28    35    42    49
</pre>

3. Write a method named swap that, given a positive integer n a parameter, computes (Hint - Do not use Strings!) and returns a new integer in which the units and tens digits have swapped places. For example, if n = 123, the result should be 132; if n = 3, the tens digit is zero and the result should be 30.

4. Invent three ways to express the XOR (“exclusive OR”) operation in Java (that is, write three different boolean methods that take two boolean variables and return true if and only if exactly one of the two variables has the value true). Hint: one of the possible solutions involves only one (relational) operator.


5. Write a method sumDigits that calculates and returns the sum of all the digits of a given non-negative integer.

6. Pretending that the modulo division operator ( % )does not exist in Java, write a boolean recursive method named isDivisibleBy3 that tests whether a given number is evenly divisible by 3. A number is divisible by 3 if and only if the sum of its digits is divisible by 3. Use your sumDigits method.

7. Write a method called printStars to print one line of stars centered. It takes how many stars and how wide the line should be.

8. Write a method named printMoreStars that takes in a parameter int n and prints out the following (either iteratively or recursively, but extra street cred for using recursion): 

For this particular example, the parameter you get is 4. (Find the relationship between the parameter passed and the number rows you need to print first.)

                   *
              *    *    *
         *    *    *    *    *
    *    *    *    *    *    *    *
         *    *    *    *    *
              *    *    *
                   *


9. Write a method named leastCoins that takes in an int cents. Your method should print the combination of coins that will add up to cents, but using the fewest total number of coins possible. (Note: only use quarters, dimes, nickels, and pennies)

10. Write a method named coins that also takes in an int cents. This method though should instead print every possible combination of coins that would add up to cents amount. It should then output the total number of combinations possible. HINT - You will need to use nested loops. (Note: only use quarters, dimes, nickels, and pennies)

