---
layout: default
title: "GLRT Example"
---

# 一个最小可运行的示例项目

下面展示一些复杂的 LaTeX 模块，包括 **定理 (Theorem)**、**命题 (Proposition)** 和 **证明 (Proof)**。

---

## 定理与证明

### Theorem
$$
\textbf{Theorem.}\quad
\text{Let $A$ be a positive definite matrix. Then all eigenvalues of $A$ are positive.}
$$

### Proof
$$
\begin{aligned}
&\text{For any nonzero vector $x$, we have } x^T A x > 0. \\
&\text{Let $\lambda$ be an eigenvalue with eigenvector $v \neq 0$, so } Av = \lambda v. \\
&\text{Then } v^T A v = \lambda v^T v > 0, \text{ which implies } \lambda > 0.
\end{aligned}
$$
$\square$

---

### Proposition
$$
\textbf{Proposition.}\quad
\text{If $X \sim \mathcal{N}(0,1)$, then $X^2 \sim \chi^2(1)$.}
$$

### Proof
$$
\begin{aligned}
&\text{By definition, a chi-square distribution with 1 degree of freedom} \\
&\text{is the distribution of the square of a standard normal random variable.} \\
&\text{Hence the claim follows directly.}
\end{aligned}
$$
$\square$
