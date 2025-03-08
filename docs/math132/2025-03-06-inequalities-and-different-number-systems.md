# Inequalities and Different Number Systems
## Inequalities
There's a difference between these two:
$$a < b: a \text{ is smaller than } b$$
$$a \leq b : a \text{ is smaller than or equal to } b$$
### Case 1. Integers
Simply enough.

### Case 2. Decimal numbers
E.g. if you have two numbers, $1.209$ and $1.211$. Compare each of the digits going from left to right.

The difference is the 3rd digit in both, $0$ and $1$, which $1$ is obviously larger and $2$ is obviously smaller, therefore $1.209 < 1.211$.

### Case 3. Negative numbers
-b, -a, 0, a, b
$$a < b \to -a > -b$$
When you flip the sign, you flip the inequality.

Example: comparing -10 and -5. Which one is bigger? -5 is bigger. Why? Because you compare the positives, which 10 is the larger, but when you change the sign, the larger becomes the smaller. Less than becomes greater than:

$$10 > 5 \to -10 < -5$$
Also, all positive numbers are greater than negative numbers.

### Case 4. Fractions
Let's say you have
$$\frac{5}{8}, \frac{6}{8}$$
Which one's bigger? Of course $\frac{6}{8}$. Why? Because $6 > 5$, and they share the same denominator. When do we have a problem? When the denominators are different.

What if the denominators are different?

You have the same problem when you add and subtract fractions. Therefore, find the LCM and convert them to have the same denominator. That is the key.

**Make equal denominators.**

Example:
$$\frac{2}{5}, \frac{3}{7}$$
It's hard to tell which one's bigger just by eyeballing. So, instead, change them to have a denominator in common:

$$\frac{2 \cdot 7}{5 \cdot 7}, \frac{3 \cdot 5}{7 \cdot 5} = \frac{14}{35}, \frac{15}{35}$$
Now we can finally compare these two:
$$\frac{14}{35} < \frac{15}{35} \to \frac{2}{5} < \frac{3}{7}$$
Interestingly, their difference is very small, only $\frac{1}{35}$.

---

### Exercise

$$-\frac{7}{9} > \frac{9}{11}$$
Note: They're negative, so the lower one is bigger.
$$\frac{-7 \cdot 11}{9 \cdot 11}, \frac{-9 \cdot 9}{11 \cdot 9} = \frac{-77}{99}, \frac{-81}{99}$$
Now $-77$ is actually the larger one and $-81$ is the smaller, so:
$$\frac{-81}{99} < \frac{-77}{99} \to \frac{-9}{11} < \frac{-7}{9}$$

The question refers to greater than so, rewritten, it's:

$$\frac{-77}{99} > \frac{-81}{99} \to \frac{-7}{9} > \frac{-9}{11}$$

---

## Different number systems

Recall $a^n = a \times a \times \dots \times a \text{ (n times)}$

In particular,
$$10^0 = 1$$
$$10^1 = 10$$
$$10^2 = 10 \times 10 = 100$$
$$10^3 = 10 \times 10 \times 10 = 1000$$
$$\dots$$
$$10^n = 10 \dots 0 \text{ ($n$ zeroes)}$$
Therefore, $10^7 = 10,000,000 \text{ (7 zeroes)}$.

Decomposing $217$:
$$217 = 200 + 10 + 7$$
$$=(2 \times 100) + (1 \times 10) + (7 \times 1)$$
$$=(2 \times 10^2) + (1 \times 10^1) + (7 \times 10^0)$$
Therefore, each column (ones, tens, hundreds, thousands, etc.) in a decimal power system is expressed by $base^\text{column}$.

---

$$2017 = 2000 + 0 + 10 + 7$$
$$=(2 \times 10^3) + (0 \times 10^2) + (1 \times 10^1) + (7 \times 10^0)$$
(usually we drop it when there is a $0 \times$, an empty column. We also drop the final one sometimes, making it end in $+ 7$)

---

Longer example

$$9080051$$
I can write the powers underneath to do a shortcut:
$$9080051$$
$$6543210$$
$$\frac{9080051}{6543210}$$
$$=(9 \times 10^6) + (8 \times 10^4) + (5 \times 10) + 1$$
(Instead of $10^1$, I just wrote 10. And I dropped all 0 columns, and I dropped the $\times 10^0$ bit.)

---

The converse example:

$$4 \times 10^5 + 6 \times 10^3 + 2 \times 10^2$$
Highest exponent is 5, so I will write down all the columns:

$$54321$$
I will fill in all the positions (4 at column 5, etc.):
$$\frac{40620}{54321}$$
Therefore,
$$4 \times 10^5 + 6 \times 10^3 + 2 \times 10^2 = 40,620$$
---

Remember, in $10^5$, $10$ is the base and $5$ is the exponent.

Can we express any number with a different base? Yes!

For example, what about Base 2? That's binary.

$$1 \times 2^2  + 1 \times 2^0 = 101 \text{ (binary)}= 4 + 1 \text{ (decimal) = 5}$$
In base 2 number, it is written $101$:
$$\frac{101}{210}$$
Where each bottom number is the exponent for 2.
