# Defining the quadratic function

## Defining the function from Points
To define the function we can use the basic formula of quadratics and the Vertex Formula:
$$
\begin{align*}
f(x) &= ax^2 + bx + c \rightarrow \text{Basic Formula} \\
\text{And} \\
f(x) &= a(x - u)^2 + v \rightarrow \text{Vertex Formula}
\end{align*}
$$
There are three ways to define it:
1. This has 3 Unknown values, which means we need 3 equations | Information is needed.
2. Vertex is given, which means the vertex formula only has a single unknown variable. Which means one additional point is needed to define the functional function.
3. Is there a third way?


### Example 1
Define a function, so that it goes through the points $P(1, -1)$, $Q(2, 4)$ and $R(4, 8)$

Basic Formula: $\displaystyle y = ax^2 + bx + c$
Point P: $\displaystyle -1 = a * 1^2 + b * 1 + c$
Point Q: $\displaystyle 4 = a * 2^2 + b * 2 + c$
Point R: $\displaystyle 8 = a * 4^2 + b * 4 + c$

$$
{\left|
    \begin{align*}
    -1 &= a + b + c \\
    4 &= 4a + 2b + c \\
    8 &= 16a + 4b + c
    \end{align*}
\right|
\text{Solve 3x3 System of Equations (SoE)}
}
$$
$$
{\left|
    \begin{align*}
    -1 &= a + b + c \\
    -5 &= -3a - b \\
    4 &= 12a + 2b
    \end{align*}
\right|
    \begin{align*}\\
    (I - II) = (IV) \\
    (III - II) = (V)
    \end{align*}
}
$$

$$
{\left|
    \begin{align*}
    -1 &= a + b + c \\
    -5 &= -3a - b \\
    -6 &= 6a
    \end{align*}
\right|
    \begin{align*}
    \\
    \\
    (IV * 2)+(V) \\
    \end{align*}
}
$$

$$
\begin{align*}
a &= \underline{-1} \\
b &= -3a + 5 = 3 + 5 = \underline{8} \\
c &= -1 - a - b = -1 + 1 - 8 = \underline{-8} \\
\rightarrow f(x) &= \underline{\underline{-x^2 + 8x - 8}}
\end{align*}
$$


### Example 2
Define a function, so that it goes through the points $P(-4, 8)$, $Q(0, 0)$ and $R(10, 15)$

Basic Formula: $\displaystyle y = ax^2 + bx + c$
Point P: $\displaystyle 8 = a * -4^2 + b * -4 + c$
Point Q: $\displaystyle 0 = a * 0^2 + b * 0 + c$
Point R: $\displaystyle 15 = a * 10^2 + b * 10 + c$

$$
{\left|
    \begin{align*}
    8 &= 16a + -4b + c \\
    0 &= c \\
    15 &= 100a + 10b + c
    \end{align*}
\right|
\text{Solve 3x3 System of Equations (SoE)}
}
$$

$$
{\left|
    \begin{align*}
    8 &= 16a + -4b \\
    15 &= 100a + 10b
    \end{align*}
\right|
\text{Multiply I by 5 and II by 2}
}
$$

$$
{\left|
    \begin{align*}
    40 &= 80a - 20b \\
    30 &= 200a + 20b
    \end{align*}
\right|
\text{Add I and II}
}
$$

$$
{\left|
    \begin{align*}
    70 = 280a
    \end{align*}
\right|
\text{Shorten it}
}
$$
$$
{\left|
    \begin{align*}
    \frac{1}{4} = a
    \end{align*}
\right|
\text{Replace this, in one of the previous functions, to get B}
}
$$

$$
{\left|
    \begin{align*}
    8 &= 16a + -4b \\
    &\downarrow \\
    8 &= 16 * \frac{1}{4} - 4b \\
    8 &= 4 - 4b \\
    4 &= -4b \\
    4b &= -4 \\
    b &= -1
    \end{align*}
\right|
\text{Multiply I by 5 and II by 2}
}
$$


## Defining function from 2 points

### Example 1
Define a function, so that it goes through the points $S(-1, 0)$ and $P(1, 3)$

Vertex formula: $f(x) = a(x - u)^2 + v$

Fill in values from points: $f(x) = a(x + 1)^2 + 0 = a(x + 1)^2$

Fill in $P$: $3 = a(1 + 1)^2 = a * 2^2 = 4a$
Calculate $a = \frac{3}{4}$
Then: $f(x) = \frac{3}{4}(x + 1)^2$
And then convert to basic formula:

$$
\begin{align*}
f(x) &= \frac{3}{4}(x^2 + 2x + 1) \\
&= \underline{\underline{\frac{3}{4}x^2 + \frac{3}{2}x + \frac{3}{4}}}
\end{align*}
$$

### Example 2
Define a function, so that it goes through the points $S(2, 1)$ and $P(0, 4)$

Vertex formula: $f(x) = a(x - u)^2 + v$

Fill in values from points: $f(x) = a(x - 2)^2 + 1 = a(x - 2)^2 + 1$

Fill in $P$: $4 = a(0 - 2)^2 + 1 = a * 4 + 1$ 
Calculate $a = \frac{4 - 1}{4} = \frac{3}{4}$ 
Then: $f(x) = \frac{3}{4}(x - 2)^2 + 1$ 
And then convert to basic formula: 
$$ \begin{align*} 
f(x) &= \frac{3}{4}(x^2 - 4x + 4) + 1 \\ 
&= \frac{3}{4}x^2 - 3x + 3 + 1 \\
&= \underline{\underline{\frac{3}{4}x^2 - 3x + 4 }}
\end{align*} 
$$
