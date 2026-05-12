# Classification with Support Vector Machines

Deck 12 of the [Mathematics for Machine Learning &mdash; Companion Series](https://github.com/BrendanJamesLynskey/MML_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/MML_12_Support_Vector_Machines/

Separating hyperplanes &amp; the maximum-margin idea, primal hard-margin SVM,
soft-margin slack, the Lagrange dual, support vectors, and the kernel trick
(linear, polynomial, RBF). Interactive 2D kernel SVM demo where you place
points and watch the decision boundary change kernel.

## What's inside

- Linear classifiers as affine hyperplanes (deck 02 connection)
- Geometric margin and the maximum-margin principle
- Primal hard-margin SVM: a constrained convex QP
- Soft-margin SVM with slack variables and the hinge loss
- The Lagrange dual (deck 07 in action) and its geometric reading
- KKT conditions identifying support vectors
- The kernel trick &mdash; replace $\mathbf{x}^\top\mathbf{x}'$ with $k(\mathbf{x},\mathbf{x}')$
- Common kernels: linear, polynomial, RBF
- Numerical solution: SMO and modern coordinate-ascent solvers
- Interactive 2D playground: add labelled points, choose kernel, see boundary

Companion to chapter 12 of:

> Deisenroth, M. P., Faisal, A. A. &amp; Ong, C. S. (2020). *Mathematics for Machine Learning.* Cambridge University Press. Free PDF: [mml-book.github.io](https://mml-book.github.io/).

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
