#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n), because the while loop is technically a < 3n and inside is a = a + 2n so when you drop the coefficients it becomes a < n and a = a + n or just n complexity.


b) O(n^2), because the outside for loop is of n complexity but the inside while loop is also of n complexity and because they are nested it becomes n * n or n^2.


c) O(n), although recursion in this case may seem to make the function more complex, it is actually only running through n number of times. Since the if and the return are only 2 operations they can be ignored we just keep doing those two things with the 2nd return as well n number of times, therefore n.

## Exercise II
For this exercise I would use a recursion type of algorithm. Since the number of floors could be used as a list, what I would do is take the middle point of the list and "check from that floor" if the egg breaks then I will recheck the middle index but of the left half of the original list, if it doesn't break then I would check the right half. I would keep breaking down the list by halves until I find the floor that the eggs would begin to break at.

Since the function would drop half the list each runthrough you could say that it would be O(n/2) but since we do not take into account coefficients it would be O(n). 

