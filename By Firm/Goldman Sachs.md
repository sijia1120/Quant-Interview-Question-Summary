# 高盛面经总结

**Engineering OA**  
三小时7道数学题 + 2道编程题  

---

## 1. Is Possible

- Consider a pair of integers, `(a, b)`. The following operations can be performed on `(a, b)` in any order, zero or more times:
  - `(a, b) → (a + b, b)`
  - `(a, b) → (a, a + b)`
- Return a string that denotes whether or not `(a, b)` can be converted to `(c, d)` by performing the operation zero or more times.

**中文说明：**

考虑一对整数 `(a, b)`。可以以任意顺序、零次或多次执行以下操作：
- `(a, b) → (a + b, b)`
- `(a, b) → (a, a + b)`

返回一个字符串，表示是否可以将 `(a, b)` 转换为 `(c, d)`。

---

## 2. Palindrome Counter

A palindrome is a string that reads the same from the left and from the right.  
For example, `"mom"` and `"tacocat"` are palindromes, as are any single-character strings.

Given a string, determine the number of its substrings that are palindromes.

**Example:** The string is s = 'tacocat'.
Palindromic substrings: [“t”, “a”, “c”, “o”, “a”, “a”, “t”, “coc”, “acoca”, “tacocat”]. There are 10 palindromic substrings. 

**中文说明：** 回文串是从左到右和从右到左读都相同的字符串。  例如 `"mom"`、`"tacocat"` 都是回文串，单字符也都是回文串。给定一个字符串，要确定其中有多少个回文字串. 


## 3. Probability and Statistics - Party Group Size

You are hosting a party where:

- Half the people arrive in groups of **6**

- Half the people arrive in groups of **2**

**Question:** What is the average group size?


## 4. Probability and Statistics - Simple Probability

Let `X` have the probability density function:

$f_X(x) = 0.5 * e^{- |x|},   where -∞ < x < ∞$

**Question:**  

What is the probability that `|x|` falls between **2 and 4**?  Round your answer to **three decimal places**.

---

## 5. Calculus - Sphere

- The radius `r` of a sphere is increasing at the uniform rate of 0.3cm per second. At the instant when the surface area S becomes 100pi cm ^2, what is the rate of increase, in cm^3 per second, in the volume V?

---

## 6. Calculus - Function

If f(x) = ln(x) / x,   for x > 0, which of the following is true? pick one option 
- `f` is increasing for all `x > 0`

- `f` is increasing for all `x > 1`

- `f` is decreasing for all `0 < x < 1`

- `f` is decreasing for all `x > e`

---

## 7. Linear Algebra - Subspaces

Let $X_0$ be a least squares solution to $Ax=b$. Which of the following statements is true in general about the residual $r = A X_0 - b$? 
- `r` is the projection of `b` onto the null space of `Aᵀ`

- `r` is the projection of `b` onto the column space of `A`

- `r` is perpendicular to `b`

- `r` lies in the null space of `A`


## 8. Probability and Statistics - Bag of Coins

- You are given a bag of coins with varying biases. The probability of heads is a random variable sampled from uniform distribution U[0,1]. You draw a coin from this bag and toss it 100 times, what is the probability of getting 100 heads? 