[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly)

---
Title: Loop the Loop! Two Dimensional Sums<br>
Type: Coding Challenge <br>
Duration: "0:30"<br>
Creator: Karolin Rafalski<br>
Adapted for SEIR<br/>
Competencies:  Arrays, Loops, Breaking down a problem into smaller steps<br>
Prerequisites: JavaScript or Python Fundamentals<br>

---

### Loop the Loop: 2D Array Addition

**Make a function that returns the greatest sum of a row, column or diagonal from a two dimensional array**


Make a function that takes one argument, a two dimensional array, where all the arrays are the same length, and returns the greatest sum of the numbers by row, column and diagonal.
```
const arr = [ [10, 20, 30],
            [40, 50, 60],
            [70, -80, 90] ];

greatestSum(arr); //180
```

#### Bonus


Test your function on this data set and let me know if it was a row, column or diagonal that had the greatest sum!

```
const bigArray =
[ [ 887, -541, -430, -590, 117, 172, -319, -18 ],
  [ -269, 964, 209, 840, -456, 156, 365, -568 ],
  [ 289, -41, 488, 198, 240, 124, -427, 214 ],
  [ 452, 894, 968, -149, 683, 977, 741, -805 ],
  [ 181, -714, -950, 107, 800, 751, -143, 380 ],
  [ 152, 493, 707, 914, 37, 356, -625, 608 ],
  [ -345, 906, 83, 676, 723, 381, 557, -183 ],
  [ 199, -943, -710, 565, 193, 315, 281, 245 ] ];
```

**Super Bonus**<br>

Create a function that takes one argument, an integer, that makes a 2D array of random integers between 0  and 1000 where the length of the rows and columns is determined by the argument.

Add a 30% chance that the integer will become negative.

**Was this TOO EASY?**<br/>
Sign up for [codewars](codewars.com) and choose a code challenge (in JavaScript) or three and solve them. Found a fun one? Share it in slack!
