List Exercises 2
=====================
*Write the code for these problems in a file called `list_primes.py` inside of the `01-list-primes` directory of this repository.*

1. Create a list called `primes` and fill it with the first two prime numbers. Hint: a prime number is a positive number that is not divisible by anything except 1 and itself.

2. Try to add the next prime number to the `primes` list by typing `primes + 5`.  What happens? 
we got an error

3. If you got an error, what does this error mean?
cannot add a non-list item to a list

4. Commit your code.
4. Fix the error (if you got one), so that 5 will be added to the list.

5. Use the statement `primes.append(7,11)` to add the next two prime numbers to the primes list. What happens? error message

6. If you got an error, what does this error mean? append method takes only one argument

7. Use the statement `primes.append([7,11])` to add the next two prime numbers to the primes list. What happens? (Hint: you may have to print primes to see) holds 7 and 11 as a separate list in the 3rd index spot. [2,3,5,[7,11]]

8. Use the `.pop()` method on primes to remove this erroneous entry.

9. Commit your code.

9. Fix the above statement and the `.append()` method twice to properly add 7 and 11 to the primes list.
10. Use the statement `primes.extend(13,17)` to add the next two prime numbers to the primes list. What happens? 

error - extend method only takes one argument

11. If you got an error, what does this error mean? can't add a list via the extend method, as it cannot accept >1 argument

12. Use the statement `primes.extend([13,17])` to add the next two prime numbers to the primes list. What happens? 

it works


*** A prime number is a natural number greater than 1 that has no positive divisors other than 1 and itself.
