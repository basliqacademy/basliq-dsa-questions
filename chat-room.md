#  [Chat room](https://codeforces.com/problemset/problem/58/A) <sup>(1s, 256MB)</sup>

Vasya has recently learned to type and log on to the Internet. He immediately entered a chat room and decided to say hello to everybody.

Vasya typed the word `s`. It is considered that Vasya managed to say hello if several letters can be deleted from the typed word so that it resulted in the word `hello`. For example, if Vasya types the word `ahhellllloou`, it will be considered that he said hello, and if he types `hlelo`, it will be considered that Vasya got misunderstood and he didn't manage to say hello.

Determine whether Vasya managed to say hello by the given word s.

### Input

The first and only line contains the word `s`, which Vasya typed. This word consists of small Latin letters, its length is no less that 1 and no more than 100 letters.

### Output

 If Vasya managed to say hello, print `YES`, otherwise print `NO`.

### Example 1

Input | Output
:- | :-
Ahhellllloou | YES

### Example 2

Input | Output
:- | :-
Hlelo | NO
