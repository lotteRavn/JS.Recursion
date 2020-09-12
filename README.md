Assignment JS.Recursion.0
There is a mathematical koncept, factorial, important in probability and statistics. The definition of n!:

n! = n * (n-1) * (n - 2) * ... * 2 * 1

There is a genuinely recursive definition that is, perhaps, more elegant:

n! = n * (n - 1)!

Write a recursive function fact(n) that calculates the factorial of a given natural number n. Document it with a couple of testcases. Place the function in myRecurseLib.js.



Assignment JS.Recursion.1
There is a mathematical koncept, Fibonacci numbers, important in various contexts eg closely related to calculating the golden ratio. The definition of the n-th Fibonacci number Fn:

F0 = 0; F1 = 1;

and:

Fn = Fn-1 + Fn-2

Write a recursive function fibo(n) that calculates the n-th Fibonacci number. Document it with a couple of testcases. Save the function in myRecurseLib.js.

Ref: https://en.wikipedia.org/wiki/Fibonacci_number

Assignment JS.Recursion.2
The mathematical powers, eg 27, or 34 may be calculated recursively.

Write a recursive function pow(r, e) that calculates re. It must work for r ∈ ℕ, and e ∈ ℕ. You might test whether it also works for r ∈ ℤ, and e ∈ ℤ

Put it into your myRecurseLib.js.

Assignment JS.Recursion.3
Write an HTML5 page in which you can input phrases to be checked for being palindromes. A common definition of a palindrome is

A palindrome is a word or a phrase that reads the same backwards and forwards.
A recursive definition of a palindrome is

A palindrome is a word or a phrase whose first and last characters match, and whatever is between the first and last characters is a palindrome.
You have previously created a small function library, jsTextUtils.js with the functions first, last, and middle. In this assignment we have to use them.

Two letter words are palindromes if the two letters are the same. One letter words are per definition palindromes. It is a convention that multiword phrases are palindromes if they read the same from the front and the back not considering spaces and punctuation. Palindromes are also case insensitive.
Now, using the recursive definition af palindromes, write a recursive function isPalindrome(s) which accepts a phrase as input, and returns true if the phrase is a palindrome, and false otherwise. Use the previously defined and tested functions.

It is a development idea to code the solution first as if palindromes are just one word. Then when the code works, change it to cater for spaces, punctuation, and case.
