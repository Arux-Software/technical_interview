The purpose of this task is to learn how you think through a problem, how you approach finding a solution, and how you iterate over ideas.

As you work on these tasks we want to hear what you're thinking and attempting. It's fine to make a mistake. It's fine to try things and realize they don't work. You're not expected to get it just right on your first attempt.

Ask questions as you have them, and be prepared to discuss your choices when you are done.

1. In your programming language of choice, write code that will print a 12 by 12 multiplication table.

Example Output:

```
1 2 3 4 5 6 7 8 9 10 11 12
2 4 6 8 10 12 14 16 18 20 22 24
3 6 9 12 15 18 21 24 27 30 33 36
4 8 12 16 20 24 28 32 36 40 44 48
5 10 15 20 25 30 35 40 45 50 55 60
6 12 18 24 30 36 42 48 54 60 66 72
7 14 21 28 35 42 49 56 63 70 77 84
8 16 24 32 40 48 56 64 72 80 88 96
9 18 27 36 45 54 63 72 81 90 99 108
10 20 30 40 50 60 70 80 90 100 110 120
11 22 33 44 55 66 77 88 99 110 121 132
12 24 36 48 60 72 84 96 108 120 132 144
```

2. Modify the function to allow the multiplication table to be formatted so each number is right aligned

Example Output (align: :right): 

```
 1   2   3   4   5   6   7   8   9  10  11  12
 2   4   6   8  10  12  14  16  18  20  22  24
 3   6   9  12  15  18  21  24  27  30  33  36
 4   8  12  16  20  24  28  32  36  40  44  48
 5  10  15  20  25  30  35  40  45  50  55  60
 6  12  18  24  30  36  42  48  54  60  66  72
 7  14  21  28  35  42  49  56  63  70  77  84
 8  16  24  32  40  48  56  64  72  80  88  96
 9  18  27  36  45  54  63  72  81  90  99 108
10  20  30  40  50  60  70  80  90 100 110 120
11  22  33  44  55  66  77  88  99 110 121 132
12  24  36  48  60  72  84  96 108 120 132 144
```

3. Modify the function to print a formatted multiplication table of any size, taking a min and max for arguments.

Example Output (min: 9, max: 13, align: :right):

```
 81   90   99  108  117
 90  100  110  120  130
 99  110  121  132  143
108  120  132  144  156
117  130  143  156  169
```

4. Modify the function to accept a string to use as a delimiter between numbers in each row

Example Output (delimiter: " |", align: :right):

```
  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 | 10 | 11 | 12
  2 |  4 |  6 |  8 | 10 | 12 | 14 | 16 | 18 | 20 | 22 | 24
  3 |  6 |  9 | 12 | 15 | 18 | 21 | 24 | 27 | 30 | 33 | 36
  4 |  8 | 12 | 16 | 20 | 24 | 28 | 32 | 36 | 40 | 44 | 48
  5 | 10 | 15 | 20 | 25 | 30 | 35 | 40 | 45 | 50 | 55 | 60
  6 | 12 | 18 | 24 | 30 | 36 | 42 | 48 | 54 | 60 | 66 | 72
  7 | 14 | 21 | 28 | 35 | 42 | 49 | 56 | 63 | 70 | 77 | 84
  8 | 16 | 24 | 32 | 40 | 48 | 56 | 64 | 72 | 80 | 88 | 96
  9 | 18 | 27 | 36 | 45 | 54 | 63 | 72 | 81 | 90 | 99 |108
 10 | 20 | 30 | 40 | 50 | 60 | 70 | 80 | 90 |100 |110 |120
 11 | 22 | 33 | 44 | 55 | 66 | 77 | 88 | 99 |110 |121 |132
 12 | 24 | 36 | 48 | 60 | 72 | 84 | 96 |108 |120 |132 |144
 ```
