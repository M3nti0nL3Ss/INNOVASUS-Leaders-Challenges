# Back-End team Challenges

Below are a handful of quick challenges for back-end candidiates. Tackle whichever challenge you'd like (unless we asked you to solve a specific challenge).

We use Python pervasively throughout our backend codebase; we would like to see you complete at least one of these challenges using Python; then feel free to use any programming language that you're comfortable with.

# Problem 1: A Plus B

Serghini is sitting in math class, on his laptop. Clearly, he is not paying attention in this situation. However, he gets called on by his math teacher to do some problems. Since his math teacher did not expect much from Serghini, he only needs to do some simple addition problems. However, simple for you and I may not be simple for Serghini , so please help him!

## Input Specification

The first line will contain an integer N (1≤N≤100000), the number of addition problems Serghini needs to do. The next N lines will each contain two space-separated integers whose absolute value is less than 1000000000, the two integers Serghini needs to add.

## Output Specification

Output N lines of one integer each, the solutions to the addition problems in order.

## Sample Input

```
2
1 1
-1 0
```

## Sample Output

```
2
-1
```

# Problem 2: Stable zeroing

Azuz, the scientific committee chair (has been doing nothing scientific anyway), started to learn how to code lately. He enjoyed the idea behind stable sorting and decided to make an interesting "stable zeroing" problem.

The idea behind stable zeroing is easy enough, you just need to move all the zeros to the end of the array, while leaving the non-zero elements in the same order they were before.

Your task is, giving an array, stable zero it!

## Input Specification

The first line of the array contains an integer 1≤n≤105 denoting the size of the array. The second line of the input contains n integers, the elements of the array (the elements can be very large up to 1018 and can be negative as well).

## Output Specification

Output the resulting array after the transformation separated by 2 spaces.

### Sample Input

```
3
1 0 2
```

### Sample Output

```
1  2  0
```

### Sample Input

```
5
1 0 2 0 3
```

### Sample Output

```
1 2 3 0 0
```

# Problem 3: Help parent

All governments find that a lock-down is the best solution to stop coronavirus from spreading with minimizing human interaction. So the work and study from home became the new lifestyle of 7 billion people around the world. But this step gives extra work for parents because beside their responsibilities as employees, they have to study with their children and monitor their performance, and spelling errors are one of the problems which face their children. Here comes your impact as a software engineer. You have to write a program which automates the correction of misspellings.

## Input Specification

The first line of the input file contains a single integer N (1 ≤N≤1000) which is the number of cases to follow.

Each case takes a line and each line contains a number M followed by a space then a single String composed by capital letters. ( M represents the index of wrong character which you have to erase it).

M will be less than or equal to the word size, and the word size is guaranteed to be below 80.

## Output Specification

For each case, you must generate a Number and String separated with space. Number represents the order, String is the correction of the given word.

### Sample Input

```
    4
    4 MISISPELL
    1 OPROGRAMMING
    7 CONTESTT
    3 BAKLLOON
```

### Sample Output

```
    1 MISSPELL
    2 PROGRAMMING
    3 CONTEST
    4 BALLOON
```

# Problem 4: Merge them up

Given two sorted arrays A and B of length up to 106 print the intersection of both arrays. The intersection of two arrays, is a sorted array that contains every element that occurs at least once in both arrays. see examples for more detail.

## Input Specification

The first line contains two integers 1≤N,M≤106 the length of array A and length of array B.

Second line contains N numbers 1≤ai≤109.

Third line contains M numbers 1≤bi≤109.

## Output Specification

if the arrays have no elements in common print "Empty" without quotes otherwise print the sorted list of the intersection of the arrays.

## Sample Input

```
1 2
1
4 7
```

Sample Output

```
Empty
```

Sample Input

```
4 3
1 2 2 3
2 3 5
```

Sample Output

```
2 3
```

Sample Input

```
4 4
1 2 2 3
1 2 2 5
```

Sample Output

```
1 2 2
```

### Notes

The given arrays are sorted in non-decreasing order.
