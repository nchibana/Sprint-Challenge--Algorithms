#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Given input n, the runtime of this algorithm would be O(n) because as the input increases, the number of operations increases linearly.
The number of operations increases by one as n increases by the same amount.


b) The runtime of this algorithm is O(n log(n)) because there is a nested while loop inside of a for loop. The outer loop is O(n), while
the while loop is O(log(n)) because the j doubles in value after each iteration. Multiplying the two gives the answer of O(n log(n)).


c) The runtime of the algorithm is O(1^n) because the formula for the run time of a recursive algorithm is O(m^n), where m is the number of
recursive calls. In this case, there is one.

## Exercise II

We can use binary search for this. First, throw one egg from the n/2 story of the building. If it breaks, we know that f cannot be higher than n/2 but lower. 
(In the other case, if the first egg doesn't break, we can eliminate the bottom half and drop the next egg from 3n/4 story.) So we can eliminate the top half of the building and 
drop the next egg from n/4 story. If it still breaks, we can drop from n/8 story, and so on, until we find a point where it doesn't break and keep dividing in 
half to find the exact story.

The runtime complexity of binary search is O(log(n)).


