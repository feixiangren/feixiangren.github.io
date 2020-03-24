Machine Learning Algorithms - A Brief Overview. Series on Vol.2 of my planning book, this is Artificial Intelligence Algorithms part.

Support Vector Machine is a machine learning for classification problem

## Mathematics Prerequisite
* Hyperplane
* Mathematical Optimization Problem, Constraint Function - Convex Optimization
* Linear Programming - Convex Optimization
* Duality - Convex Optimization
* Lagrange Function - Multivariable Calculus

### Hyperplane

In a %%p%%-dimensional space, a hyperplane is a flat affine subspace of hyperplane dimension %%p%%. It is mathematically defined as:

$$\beta_0 + \beta_1X_1 + \beta_2X_2 + \ldots + \beta_pX_p = 0 \quad(1)$$

the hyperplane devides %%p%%-dimensional space into two halves:

$$\beta_0 + \beta_1X_1 + \beta_2X_2 + \ldots + \beta_pX_p > 0 \quad(2)$$

$$\beta_0 + \beta_1X_1 + \beta_2X_2 + \ldots + \beta_pX_p < 0 \quad(3)$$

so we can easily determine which side the point lies by calculating the sign.

$$
x_1 =
\begin{pmatrix}
   x_11 \\
   \vdots \\
   x_1p
\end{pmatrix}
,\cdots,
x_n =
\begin{pmatrix}
   x_n1 \\
   \vdots \\
   x_np
\end{pmatrix}
\quad(4)
$$

## Support Vector Machine
One of best way to do Classification problem. We try and find a plane that separates the classes in feature space.

### Reference
* [An Introduction to Statistical Learning, 2nd Edition]()
