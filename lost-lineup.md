#  [Lost Lineup](https://open.kattis.com/problems/lostlineup) <sup>(1s, 1024MB)</sup>

Jimmy and his friends were all standing in a lineup for ice cream when a huge gust blew them all around. The friends want to keep things fair and make sure everyone gets their ice cream in the order they started with. The friends do not remember the order, but each of them remember exactly how many people were between them and Jimmy. Jimmy is always the first person in line. Can you help him and his friends remember the order?

### Input

The first line contains a single integer $n$ ($1 \leq n \leq 100$), the number of people in the line. The second line contains $n - 1$ space separated integers, where $d_i$ ($0 \leq d_i \leq n - 2$) is the number of people between the $(i + 1)^{th}$ person and Jimmy. Jimmy is always first in the lineup.

### Output

Print a single line with $n$ integers, the people in the order of the original lineup. It is guaranteed that there is always a unique solution.
 
### Example 1

Input | Output
:- | :-
2 <br> 0 | 1 2

### Example 2

Input | Output
:- | :-
4 <br> 1 2 0 | 1 4 2 3
