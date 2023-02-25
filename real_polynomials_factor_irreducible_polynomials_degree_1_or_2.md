# Real coefficients polynomials can always factor into irreducible polynomials of degree 1 or 2.

This is a direct consequence of the Fundamental Theorem of Algebra (FTA), as can be seen.


## Fact 1

Any non constant complex polynomial can be factored into monomials (by FTA). If the polynomial is real, then every complex root also have a its conjugate as root, because:

If $a \in \mathbb{C}$ is root of $P(x)$, a polynomial with real coefficients, then

$P(a) = 0 \implies \overline{P(a)} = \overline{0} \implies P(\overline{a}) = 0$


## Fact 2

If $a$ and $\overline{a}$ are roots or real polynomial $P(x)$, then $P(x)$ is divisibel by $(x-a)(x-\overline{a})$ and this is also a real polynomial.
There fore, if $c$ is some root of $P(x)$, then:

1) If $c$ is real, then $P(x)$ is divisible by $(x-c)$ (polynomial of degree 1).
2) If $c$ is complex, then $P(x)$ is divisible by $(x-c)(x-\overline{x})$. By Fact 1, this polynomial has real coefficients and degree 2. $\blacksquare$
