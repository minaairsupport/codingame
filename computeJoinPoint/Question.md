We consider the sequence of numbers where a number is followed by the same number plus the sum of its
digits.

For example 34 is followed by 41 (as 41 = 34 + (3 + 4)). 41 is itself followed by 46 (46 = 41 + (4 + 1)).

Two sequences which start from different numbers may join at a given point, for example, the sequence starting
from 471 and the sequence starting from 480 share the number 519 (the join point) in their sequence. After the
join point, the sequences are equal.

Implement the function computeJoinPoint (s1, s2) which takes the starting points of two sequences and then
returns the join point of these sequences


Constraints:

The given sequences always join

0 < s1, s2 < 20000000

0 < join point < 20000000


![Screen Shot 2022-10-22 at 10 50 15 PM](https://user-images.githubusercontent.com/33718103/197362348-0fec9c70-e7ff-4707-840d-1d5f600153d6.png)

![Screen Shot 2022-10-22 at 10 50 21 PM](https://user-images.githubusercontent.com/33718103/197362353-0a128269-caf5-4f60-a513-984576f3d7d6.png)
