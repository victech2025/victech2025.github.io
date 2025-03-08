# Exponentials and Fractions

## Exponentials (Powers)
Definition:
$$a^n = a \times a \times \dots \times a, \text{n times}$$
Read "$a$ to the $n$".

Example.
$$3^2 = 3 \times 3$$
Read "3 squared". $2$ above is known as the exponent. When the exponent is 2, we say squared. When the exponent is 3, we say cubed.

$$2^3 = 2 \times 2 \times 2$$
Read: "2 cubed".

Just as importantly, you can raise a power by 1. Example:
$$5^1 = 5$$
The exponent indicates how many times you need to multiply the base number.

You can raise the power of bases by negative numbers and zero.

$$n^0 = 1$$

Theorem. For any $a$,
$$a^1 = a$$
What about $a^0$?

$a^0 =$ ?
$a^1 = a$
$a^2 = a \times a$
$a^3 = a \times a \times a$

$a$ is multiplied each time, therefore to go down one you divide by $a$. Therefore, $a^0$ is $\frac{a}{a}$ which equals $1$.

Hence
$a^0 \to a^1 = a$
$x \times a = a$
$a^0 = 1$

Theorem. For any $a$ where $a \neq 0$,
$$a^0 = 1$$
Example:
$$5 \times 10^2 + 3 \times 10^1 + 2 \times 10^0$$
$$=5 \times 10 \times 10 + 3 \times 10 + 2 \times 1$$
$$=500 + 30 + 2$$
$$= 532$$
The question splits it into hundreds, tens, and ones column using the powers. $a^2$ is hundreds, $a^1$ is tens, $a^0$ is ones:
* $5 \times 10^2 = 500$ (hundreds)
* $3 \times 10^1 = 30$ (tens)
* $2 \times 10^0 = 2$ (ones)

This will come in handy later when learning binary. For Base 10 (Decimal), each column is multiplied by a power of 10, starting at 0.

For binary, which is Base 2, each column is multiplied by a power of 2. The first column is $2^0$, which represents 1, the second column is $2^1$, which represents 2, the third column is $2^2$, which represents 4 and so on. To make a number like 5, you would put 1 in the 4's column and 1 in the 1's column, making $101, \text{which in base 10 is } 4 + 1 = 5$.
## Order of Computation (BEDMAS)
Remember:
* Division and Multiplication have equal precedence, go left to right
* Addition and Subtraction also have equal precedence, go left to right

Priority:
1. B: Brackets
2. E: Exponentials
3. DM: Division and Multiplication
4. AS: Addition and Subtraction

For example, when no brackets are involved
$$2 + 3 \times 4 \div 6$$
$$= 2 + (3 \times 4) \div 6$$
$$= 2 + 12 \div 6$$
$$= 2 + (12 \div 6)$$
$$= 2 + 2$$
$$=4$$
If you are given brackets, you must compute the inside of the brackets first:
$$(2 + 3 \times 4) \div 6$$
$$= (2 + 12) \div 6$$
$$=14 \div 6$$
$$=\frac{14}{6}$$
$$=\frac{7}{3}$$ 
(**Don't forget to simplify**)

In another example, with explanations:
$$5^2 \times (2 \times 3) \div 10$$
$$= 5^2 \times 6 \div 10$$
$$= 5 \times 5 \times 6 \div 10$$
$$=25 \times 6 \div 10$$
$$=150 \div 10$$
$$=15$$
## Fractions
Math should be precise at all times, but at the same time, like all things, we have conventions.

For example: When you write fractions, for example:
$$\frac{2 \times 3 - 7}{5 + 6}$$
It's not written anywhere, but it's an unspoken rule that there is a bracket at the top and a bracket at the bottom. So the priority is computing the numerator and the denominator simultaneously.
$$\frac{(2 \times 3 - 7)}{(5 + 6)}$$
$$=\frac{6 - 17}{11}$$
$$=\frac{-1}{11}$$
$$=-\frac{1}{11}$$
You can do quick negative subtraction by swapping the numbers and then putting a negative sign at the end. E.g. $$6 - 7 = -(7 - 6) = -1$$
Fractions can get complicated. The possibilities are unlimited.

### Fractions inside fractions
Slash notation is shorthand for a fraction.

Let's say you're given:
$$1 / 6 / 1 / 3$$
$$\frac{\frac{1}{6}}{\frac{1}{3}}$$
Your result should be a fraction or an integer.

How do you convert that? There are a number of ways to do it. The lecturer's favourite is: it's best to simplify the denominator first. The denominator has a denominator of 3. If you multiply the bottom by 3, you have to multiply the top by 3 too; the fraction stays the same.
$$=\frac{\frac{1}{6} \times 3}{\frac{1}{1}}$$
$$=\frac{\frac{1}{2}}{\frac{1}{1}}$$
$$=\frac{\frac{1}{2}}{1} = \frac{1}{2}$$
(remember that $\frac{a}{1} = a$)

In case that is too overwhelming, there is a formula for it:

$$\frac{\frac{a}{b}}{\frac{c}{d}} = \frac{ad}{bc}$$
**You multiply the outside $ad$ (this will be the numerator) and the inside $bc$ (this will be the denominator).**

Therefore,
$$\frac{\frac{1}{6}}{\frac{1}{3}} = \frac{1 . 3}{6 . 1} = \frac{3}{6} = \frac{1}{2}$$
(The dot $.$ is shorthand for multiplication $\times$)

You should use improper fractions in this course, rather than making a mixed numeral, e.g.
$$\frac{3}{2} > 1 \frac{1}{2}$$
