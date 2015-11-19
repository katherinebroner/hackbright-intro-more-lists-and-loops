#Loops Exercises Part 1: Exploring Range
*Do the following exercises in the Python interpreter.*

## Explore `range`
*You do not need to type up answers to these.*

1. Type `range(5)` and press enter. What happens? [0, 1, 2, 3, 4]

2. Type `range(3.14)` and press enter. What happens? 
TypeError: range() integer end argument expected, got float.

3. Type `range(-8)` and press enter. What happens? []
4. Type `range(0)` and press enter. What happens? []
5. Type `range(1)` and press enter. What happens? [0]
6. Type `range(1,5)` and press enter. What happens? [1, 2, 3, 4]

  1. How is this different than `range(5)`? will print [0, 1, 2, 3, 4]

7. Type ``range(5,1)`` and press enter. What happens? [0]
8. Now type `range(5,1,-1)` and press enter. What happens?
[5, 4, 3, 2]
  1. How is this different than `range(5,1)`?
  Need to specify step size.

9. Type `range(0,-5)` and press enter. What happens? []

10. Type `range(-5,0)` and press enter. What happens?
[-5, -4, -3, -2, -1]

  1. How is this different than `range(0,-5)`?
Can only count from negative to positive, not vice-versa

  2. How would you get the numbers from 0 down to -4? (Hint: look at #8)
range(0,-5,-1)

11. Type `range(10)` and press enter. What happens?
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

12. Type `range(0,10)` and press enter. What happens?
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

13. Type `range(0,10,1)` and press enter. What happens?
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

14. Type `range(0,10,2)` and press enter. What happens?
[0, 2, 4, 6, 8]

15. Type `range(0,10,1+1)` and press enter. What happens?
[0, 2, 4, 6, 8]

## Describe how `range` works
*Please record your answers to these questions by using the edit button on GitHub.  
Make sure you have pushed your lists exercises before making any commits on GitHub, otherwise you will have to make a merge commit later.*

1. What does `range` do with a single argument?
  * Assumes count starts at zero with increments of 1 up to the range parameter value minus 1.  Range parameter value must be a positive number.
2. What do the arguments mean if there are 2?
  * Count starts with the first parameter with increments of 1 up to the second parameter value minus 1.  Only works with range going in increasing direction (eg. negative to positive)
3. What does the third argument mean?
  * The increment that you are counting up or down by.  Cannot be a float.  
