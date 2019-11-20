# 7 Canonical Forms
## 7.1 The Jordan Canonical Form
### [Determinants](http://www.math.lsa.umich.edu/~hochster/419/det.html)
* [Gemoetric](https://math.stackexchange.com/questions/598219/effect-of-elementary-row-operations-on-determinant)

**Fact 1:** Switching any two rows of an $n \times n$ matrix $A$ reverses the
sign of its determinant

Sum of terms from expansion of first two rows have form $\left( \pm a_{1i}
a_{2j} \det{\left( B \right) } \right) $, where $B$ is the matrix formed by
omitting the first two rows and the $i$th and $j$th, $i \not= j$. Sign is
$\left( \left( -1 \right)^{i - 1} \left( -1 \right)^{(i - 1) + \left( j - i - 1 \right) }\right) = \left( \left(-1\right)^{i - 1} \left( -1 \right)^{j - 2} \right)$ if $i < j$
and is $\left( \left( -1 \right)^{i - 1} \left( -1 \right)^{j - 1}  \right)$ if
$i > j$.

**Theorem 7.1**

$\left( T - \lambda I \right)^{p}T(x) = T\left( T - \lambda I \right)^{p}\left(
x\right) = T(0) = 0$

$\left( T - \lambda I \right)^{p}$ commutes w/ $T$ b/c $T$ commutes w/ itself
and $T$ commutes w/ $I$.

**Theorem 7.2**

$h(t)$ divides the characteristic polynomial of $T$.

*Exercise 20 Section 4.3*
$\det{\left(\begin{bmatrix}
I & B
\\
0 & D
\end{bmatrix}\right)}
= \det{\left(\begin{bmatrix}
I & 0
\\
B^{\top} & D^{\top}
\end{bmatrix}\right)} = \det{\left( D^{\top} \right)} = \det{\left( D \right) }$

**Theorem 7.3**

$W = R\left( \left( T - \lambda_{k} I \right)^{m} \right)$ $T$-invariant
* $T\left(\left( T - \lambda_k I \right)^{m}(x)\right) = \left( T - \lambda_k I
    \right)^{m} T(x) \in R\left( \left( T - \lambda_k I \right)^{m}  \right) $
