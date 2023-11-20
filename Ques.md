

#### **Dynamic Palindrome Partitioning:**

**Challenge: Dynamic Palindrome Partitioning**
**Difficulty:  Hard**

**Problem Statement:**

You are given a challenging problem that revolves around palindromes. A palindrome is a word or phrase that reads the same backward as forward, such as "madam" or "racecar." The task at hand is to determine the minimum number of cuts required to dynamically partition a given string into palindromes.

**Input:**

You will be given a string consisting of only lowercase English letters.

**Output:**

Your solution should output an integer representing the minimum number of cuts required to dynamically partition the input string into palindromes.

**Examples:**

**Example 1:**

```markdown

Input: "aab"

Output: 1

Explanation:

The string “aab” can be dynamically partitioned into two palindromes, “aa” and “b”, using one cut. Therefore, the output is 1.

```

**Example 2:**

```markdown

Input: "aabb"

Output: 2

Explanation:

The string “aabb” can be dynamically partitioned into three palindromes, “aa,” “bb,” or “a,” “a,” “b,” using two cuts. Therefore, the output is 2.

```

**Constraints:**

- The length of the input string is between 1 and 1000 characters.

- The input string consists of only lowercase English letters.

**Additional Notes:**

- There may be multiple valid partitions for a given input string. Your code should find the partition with the minimum number of cuts.

**Test Cases:**

### Dynamic Palindrome Partitioning:

**Test Case 1:**

```markdown

Input: "abacaba"

Output: 2

```

**Test Case 2:**

```markdown

Input: "racecar"

Output: 0

```

**Test Case 3:**

```markdown

Input: "abcde"

Output: 4

```

**Test Case 4:**

```markdown

Input: "aaaa"

Output: 0

Explanation:

The string "aaaa" is already a palindrome, so no cuts are required. Therefore, the output is 0.

```

**Test Case 5:**

```markdown

Input: "abbaabba"

Output: 1

```


#### **Matrix Word Hunt:**

**Challenge: Matrix Word Hunt**
**Difficulty:  Medium**
**Problem Statement:**

Imagine a scenario where you are tasked with a word search on a 2D matrix of characters. Your goal is to find all the words from a given list within the matrix. The words can be arranged in any direction—horizontally, vertically, or diagonally.

**Input:**

- You will receive a 2D matrix of characters represented by a list of lists.

- Additionally, you will be given a list of words represented by a list of strings.

**Output:**

Your solution should provide a list of strings representing the words found in the matrix.

**Examples:**

**Example 1:**

```markdown

Input:

matrix = [

["o", "a", "a", "n"],

["e", "t", "a", "e"],

["i", "h", "k", "r"]

]

words = ["oath", "eat", "rain"]

Output:

["oath", "eat"]

```

**Example 2:**

```markdown

Input:

matrix = [

["b", "h", "n", "t", "y"],

["o", "a", "s", "i", "o"],

["t", "h", "e", "r", "e"]

]

words = ["board", "hello", "there"]

Output:

["board", "hello", "there"]

```

**Constraints:**

- The dimensions of the matrix are between 1 and 100.

- Each character in the matrix is a lowercase English letter.

- The length of each word in the list is between 1 and 20.

- Each word in the list consists only of lowercase English letters.

**Test Cases**

### Matrix Word Hunt:

**Test Case 1:**

```markdown

Input:

matrix = [

["o", "a", "a", "n"],

["e", "t", "a", "e"],

["i", "h", "k", "r"]

]

words = ["oath", "eat", "rain"]

Output:

["oath", "eat"]

```

**Test Case 2:**

```markdown

Input:

matrix = [

["b", "h", "n", "t", "y"],

["o", "a", "s", "i", "o"],

["t", "h", "e", "r", "e"]

]

words = ["board", "hello", "there"]

Output:

["board", "hello", "there"]

```

**Test Case 3:**

```markdown

Input:

matrix = [

["c", "o", "d", "e"],

["h", "a", "m", "p"],

["t", "i", "m", "e"]

]

words = ["code", "champ", "time"]

Output:

["code", "champ", "time"]

```

**Test Case 4:**

```markdown

Input:

matrix = [

["h", "e", "l", "l", "o"],

["w", "o", "r", "l", "d"]

]

words = ["hello", "world"]

Output:

["hello", "world"]

```

**Test Case 5:**

```markdown

Input:

matrix = [

["a", "b", "c"],

["d", "e", "f"],

["g", "h", "i"]

]

words = ["abc", "def", "ghi"]

Output:

["abc", "def", "ghi"]

```

---

### **Petty Cash**

**Challenge: Petty Cash**
**Difficulty:  Easy**

**Problem Statement:**

In this challenge, you are presented with the task of determining the minimum number of coins required to make up a given amount of money. You are provided with a set of coin denominations, and you have an unlimited supply of each coin denomination.

**Input:**

- An integer representing the amount of money.

- A list of integers representing the coin denominations.

**Output:**

Your solution should output an integer representing the minimum number of coins required to make up the specified amount of money.

**Examples:**

**Example 1:**

```markdown

Input:

amount = 11

denominations = [1, 2, 5]

Output:

3

Explanation:

The minimum number of coins required to make up the amount 11 using the denominations 1, 2, and 5 is 3 (3 * 5 + 2 * 1).

```

**Example 2:**

```markdown

Input:

amount = 15

denominations = [1, 2, 3, 5]

Output:

5

Explanation:

The minimum number of coins required to make up the amount 15 using the denominations 1, 2, 3, and 5 is 5 (3 * 5).

```

**Constraints:**

- The amount of money is between 1 and 1000.

- There are between 1 and 10 different coin denominations.

- Each coin denomination is between 1 and 100.

**Additional Notes:**

- There may be multiple valid solutions for a given input. Your code should find one of the valid solutions.

- You can use any programming language of your choice.

- The problem can be solved using dynamic programming techniques.

**Test Cases:**

### Petty Cash:

**Test Case 1:**

```markdown

Input:

amount = 11

denominations = [1, 2, 5]

Output: 3

```

**Test Case 2:**

```markdown

Input:

amount = 15

denominations = [1, 2, 3, 5]

Output: 5

```

**Test Case 3:**

```markdown

Input:

amount = 20

denominations = [2, 5, 10]

Output: 2

```

**Test Case 4:**

```markdown

Input:

amount = 8

denominations = [1, 4, 5]

Output: 2

```

**Test Case 5:**

```markdown

Input:

amount = 13

denominations = [2, 7, 13]

Output: 1

```
