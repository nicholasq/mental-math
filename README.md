# **Mental Math**

This information here is heavily inspired by the book 'Secrets of Mental Math' by Authur Benjamin and Michael Shermer.

## **A Small Appetizer**

### **How to multiply two-digit numbers by eleven**

**Rules:**
1. Sum the two digits from the first number.
2. If the sum of the two digits is less than 10, go to step 3, else go to step 4.
3. The result is the first digit, sum, and second digit.
4. The result is the first digit plus 1, the last digit of sum, and the last digit of the first number.

**Explanation:**

```
Example 1: 32 x 11

Step 1: Sum the two digits of 32
3 + 2 = 5

Step 2: Check if sum is less than 10
5 is less than 10, so we use Rule 3

Step 3: Write the result as:
- First digit (3)
- Sum (5)
- Last digit (2)

So: 32 x 11 = 352

Visual breakdown:
   3│2
   ↓│↓
   3│2    First & last digits
    5     Sum goes in middle
   ↓↓↓
   352


Example 2: 57 x 11

Step 1: Sum the two digits of 57
5 + 7 = 12

Step 2: Check if sum is less than 10
12 is greater than 10, so we use Rule 4

Step 4: Write the result as:
- First digit plus 1 (5 + 1 = 6)
- Last digit of sum (2)
- Last digit of original number (7)

So: 57 x 11 = 627

Visual breakdown:
     5│7
     ↓│↓
   5+1│7    First digit + 1 & last digit
     6|7
    6|2|7   Last digit of sum goes in middle
     ↓↓↓
     627
```

**Examples:**
```
32 x 11
3 + 2 = 5
352

53 x 11
5 + 3 = 8
583

81 x 11
8 + 1 = 9
891

85 x 11
8 + 5 = 13 # we need to carry the 10s place:
8 + 1 = 9
935

57 x 11
5 + 7 = 12 # we need to carry the 10s place:
5 + 1 = 6
627

77 x 11
7 + 7 = 14 # we need to carry the 10s place:
7 + 1 = 8
847

99 x 11
9 + 9 = 18 # we need to carry the 10s place:
9 + 1 = 10
1089
```

---

### **Squaring**

#### **Square a two-digit number that ends in a 5**

**Rules:**
1. The result begins by multiplying the first digit by the next higher number.
2. The result ends with `25`

**Explanation:**

```
For any number like X5 (where X is the first digit):
1. First part: Take X and multiply it by (X+1)
2. Second part: Always add 25 at the end

Example 1: 35²
    3│5
    ↓
    3 × 4 = 12   (First digit × next number)
           25    (Always ends in 25)
    Result: 1225

Example 2: 75²
    7│5
    ↓
    7 × 8 = 56   (First digit × next number)
           25    (Always ends in 25)
    Result: 5625

Think of it as:
[First digit × (First digit + 1)] | [25]
```

**Examples:**
```
35
3 x 4 = 12
5 x 5 = 25
1225

85
8 x 9 = 72
5 x 5 = 25
7225
```

---

#### **Multiply two-digit numbers with same first digit**

**Rules:**
1. The first two digits must be the same.
2. The last two digits must sum to `10`, if they do not, this technique will not work.
3. The result begins by multiplying the first digit by the next higher number.
4. The result ends with the result of multiplying the last digits.

**Explanation:**

```
83 x 87

Step 1: Check if numbers meet the rules
✓ First digits are the same (8)
✓ Last digits sum to 10 (3 + 7 = 10)

Step 2: Build the answer in two parts:

Part 1: First digits
    8│ × 9 = 72   (First digit × next number)
    ↑     ↑
    8     9        (8 followed by 9)

Part 2: Last digits
     3 × 7 = 21
     ↑   ↑
     3   7         (3 × 7)

Final result: 7,221

Visual breakdown:
    83 × 87
    8 × 9 = 72    (First part)
    3 × 7 = 21    (Second part)
    7221          (Combined)

Think of it as:
[First digit × (First digit + 1)] | [Product of last digits]
```

**Examples:**
```
83 x 87
8 x 9 = 72
3 x 7 = 21
7221

84 x 86
8 x 9 = 72
4 x 6 = 24
7224

26 x 24
2 x 3 = 6
6 x 4 = 24
624

31 x 39 = 1209
32 x 38 = 1216
33 x 37 = 1221
34 x 36 = 1224
35 x 35 = 1225
```

---

## **Addition and Subtraction**
todo

## **Basic Multiplication**
todo

## **Intermediate Multiplication**
todo

## **Mental Division**
todo

## **Guesstimation**
todo

## **Back-of-the-envelope Calculations**
todo

## **Memorizing Numbers**
todo

## **Advanced Multiplication**
todo

## **Mathematical Magic**
todo
