# Base 2 (Binary)
## Binary to decimal
Last time we broke up numbers:

$$2071 = 2000 + 70 + 1$$

$$= 2 \times 10^3 + 7 \times 10^1 + 1 \times 10^0$$

$$= 1$$

What if we use a different base that isn't 10? Base 10 is called base 10 because it uses a maximum of 10 digits to express numbers: 0, 1, 2, 3, 4, 5, 6, 7, 8, and 9.

For example, if you use 2 as the base, you only have 2 digits to represent all numbers: 0 and 1.

For example,

$$(101)_{2} = 1 \times 2^2 + 0 \times 2 ^ 1 + 1 \times 2 ^ 0$$

We can drop 1 when multiplying it by another number and can drop a column when there is a zero there (e.g. in the sequence $0 \times 2^1$, which equals $0$):

$$= 2^2 + 2^0 = 2^2 + 1$$

$$=4 + 1$$

$$= 5$$

Another example:

$$(10011)_{2}$$

Until you get used to them, I would write the indices underneath these numbers to remind you what power you should raise 2 to when a number appears in that column (the following example is not a fraction):

$$\frac{(10011)_{2}}{43210}$$

$$= 1 \times 2^4 + 1 \times 2^1 + 1 \times 2^0$$

Drop the 1s:

$$2^4 + 2^1 + 2^0 = 2^4 + 2^1 + 1$$

$$=16 + 2 + 1$$

$$=19$$

You compute each column of Base 2 by multiplying the previous column by 2 (think of how the ones, tens, and hundreds columns in base 10/decimal is achieved by multiplying the previous one by 10):


| **n**     | **0** | **1** | **2** | **3** | **4** | **5** | **6** | **7** |
| --------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| **$2^n$** | 1     | 2     | 4     | 8     | 16    | 32    | 64    | 128   |

Base 2 numbers are often called binary (bi = 2) because it only uses 2 numbers. Computers use binary numbers, and only read them natively, rather than base 10. Your email, videos, etc. are all actually stored in binary. Why? Because it's easy to electronically store that data, which only require a current to represent a 1 and its absence to represent a 0.

## Decimal to binary
### Given a sum of exponentials
Conversely,

Example. Write $2^6 + 2^4 + 2$ in base 2.

How do you do this? Just reverse what we just learned.

Note the exponents: 6, 4, and 1.

$$2^6 + 2^4 + 2 = 2^6 + 2^4 + 2^1$$

How many digits do you need? Look at the biggest exponent: 6. You'll need up to 7 digits (including $2^0$).

Represent it using the indices:

$$\frac{???????}{6543210}$$

Then whenever there is a power to $n$, go to the $n$th column and place a $1$ there:

$$\frac{1?1??1?}{6543210}$$

Then fill in the rest with zeroes:

$$\frac{1010010}{6543210}$$

Therefore, $2^6 + 2^4 + 2$ in Base 2 is $1010010$!

Simple, right?
### Given a base 10 number
But what if you're not given a sum of exponential equations? How do you convert base 10 numbers to base 2?

Base 10 numbers are conventionally called decimal numbers and Base 2 numbers are conventionally called binary numbers.

Say you have $50$ and you want to convert that. What do you do?

 1. Write a table of powers (=exponentials) of 2, less than our example number 50:

| **n**     | **0** | **1** | **2** | **3** | **4** | **5** | **6** | **7** |
| --------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| **$2^n$** | 1     | 2     | 4     | 8     | 16    | 32    | 64    | 128   |

2. Find the biggest power of 2 (not exceeding 50): the biggest in this example is $32 = 2^5$
3. You minus that biggest number from $50$: $50 - 32 = 18$
4. Then you take $18$ and you do the same thing again. The largest power of 2 not exceeding 18 is $16$ which is $2^4$.
5. Subtract that: $18 - 16 = 2$
6. Then $2$ is already on the table, it's $2^1$.

Now you have your sum of exponentials: $2^5 + 2^4 + 2^1$

That means in the binary number we produce, there should be 3 ones and the rest should be zeroes.

How many digits? Largest exponent is 5, so there are 6 digits. This makes:

$$\frac{??????}{543210}$$

Fill in the 1s according to the powers above:

$$\frac{11??1?}{543210}$$

Then fill the rest with zeroes:

$$\frac{110010}{543210}$$

$$=110010$$

Therefore,

$$50_{10} = 110010_{2}$$

---

Base 5 example (this doesn't look correct to me but that's what the tutor has written):

$$(23)_{5}$$

$$= 2 \times 5 ^3 + 3 \times 5^1$$

$$=(2030)_{5}$$
## Exercises
### Convert into base 2

Exercise 1: 84
1) Largest power is 64 / $2^6$

2) 84 - 64 = 20

3) Largest power is 16 / $2^4$

4) 20 - 16 = 4

5) Largest power is 4 / $2^2$

6) Result: $2^6 + 2^4 + 2^2 = 1010100_{2}$

Exercise 2: 32

1) Largest power is 32 / $2^5$

2) Result: $100000_{2}$

### Convert into base 10

Exercise 1: $(10100)_{2}$

1) That is $2^5 + 2^3$

2) $= 32 + 8$

3) $= 40$
