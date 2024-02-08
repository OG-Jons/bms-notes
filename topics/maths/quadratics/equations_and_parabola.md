# Quadratic Equations and Parabolas

Quadratic equations are polynomial equations of the second degree, commonly written in the form:

```math
ax^2 + bx + c = 0
```

where $`a`$, $`b`$, and $`c`$ are constants, and $`x`$ represents the variable.

## The Quadratic Formula

The solutions to a quadratic equation can be found using the quadratic formula:

```math
x = \frac{{-b \pm \sqrt{{b^2 - 4ac}}}}{{2a}}
```

## Relationship with Parabolas

Quadratic equations are closely related to the graph of a parabola. The general form of a quadratic equation can be expressed as:

```math
f(x) = ax^2 + bx + c
```

The graph of this equation is a parabola, which can open upwards or downwards depending on the sign of $`a`$.

- If $`a > 0`$, the parabola opens upwards.
- If $`a < 0`$, the parabola opens downwards.

## Example

Consider the quadratic equation $`y = 2x^2 - 4x + 2`$.

```math
y = 2x^2 - 4x + 2
```

The corresponding parabola opens upwards because $`a = 2 > 0`$.

### Drawing of the Parabola

```math
\begin{align*}
f(x) &= 2x^2 - 4x + 2 \\
&= 2(x^2 - 2x) + 2 \\
&= 2(x^2 - 2x + 1) + 2 - 2 \\
&= 2(x - 1)^2 + 0
\end{align*}
```

```math
\text{Vertex form: } f(x) = a(x - h)^2 + k
```

In this form, the vertex of the parabola is at $`(h, k)`$. For our example, the vertex is $`(1, 0)`$.

```math
\text{Vertex: } (1, 0)
```

The vertex form allows us to easily identify the vertex and understand the direction in which the parabola opens.

### Graph

![Parabola Graph](parabola_graph.png)

This graph represents the parabola $`y = 2x^2 - 4x + 2`$, with the vertex at $`(1, 0)`$ and an upward opening.


## Coefficient `b` in Quadratic Equations and Parabolas

In the quadratic equation $ax^2 + bx + c = 0$ and the function $f(x) = ax^2 + bx + c$, `b` is the coefficient of the linear term (`bx`). This coefficient has several effects on the properties of the quadratic equation and the parabola it represents:

### Example 1: Quadratic Function with $b = 0$

Consider the quadratic function $f(x) = x^2$. This function has a $b$ coefficient of 0. The graph of this function is a parabola that opens upwards and is symmetric about the y-axis (the line $x = 0$).

### Example 2: Quadratic Function with $b = 4$

Now consider the quadratic function $f(x) = x^2 + 4x$. This function has a $b$ coefficient of 4. The graph of this function is also a parabola that opens upwards, but it is not symmetric about the y-axis. Instead, it is symmetric about the line $x = -2$, which is given by the formula $x = -\frac{b}{2a}$.

Comparing these two examples, we can see that changing the $b$ coefficient shifts the parabola horizontally along the x-axis. The vertex of the parabola, which was at the origin in the first example, has moved to the point $(-2, -4)$ in the second example.

### Display

This is how the above examples behave, when displayed as a parabola

![coefficient_b](coefficient_b.png)


## Vertex (Scheitelpunktform)

### $f(x) = a(x-u)^2+v$

**Important**: $a$ is written before the parantheses, $(ax-u)^2$ is *not* a valid Vertex formula. It is required to be formed as $a(x-u)^2$

- Example 1
    Convert $f(x)=8(x+0.5)^2-1$ to the basic formula.
    - $f(x)=8(x^2+x+0.25)-1$
    - $f(x)=8x^2+8x+2-1$
    - $\underline{\underline{f(x)=8x^2+8x+1}}$
Which then means, $a=8, \space b=8, \space c=1$

- Example 2
    Convert $f(x)=3x^2-12x-18$ to the Vertex formula
    - $f(x)=3(x^2-4x-6)$ || [Complete the square](./calculating_squares.md)
    - $f(x)=3(x^2-4x+4-4-6)$
    - $f(x)=3((x-2)^2-10)$
    - $\underline{\underline{f(x)=3(x-2)^2-30}}$
