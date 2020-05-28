# Information of Binary Search
## Homework 1 of VG101
### Zhang Fan 张帆 519021911184

#### What is binary search?
> Binary search is an efficient algorithm for finding an item from a sorted list of items. It works by repeatedly dividing in half the portion of the list that could contain the item, until you've narrowed down the possible locations to just one. We used binary search in the guessing game in the introductory tutorial.
> For example, assume that there is a sorted list of integers (n1,n2,n3,...,nn) and you want to find where a number m is in the list. Here is the step to solve the problem using binary search.
1. Let min = n1, max = n2.
2. Guess a number x (often the average of min and max).
3. If x = m, you're done!
4. If m is less than the number you guess, then min = n1, max = x;
5. If m is greater than the number you guess, then min = x, max = n2;
6. Go back to step 2.

#### Reference
- https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search
