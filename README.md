# Machine Learning Foundations

The complete handwritten lecture notebook for **Machine Learning Foundations**, written by **Kshitij Maheshwari** — Weeks 1–12, 60 lectures — typeset as a single self-contained HTML book, with every diagram redrawn as a vector figure.

**Read it:** https://ammar-iitm.github.io/machine-learning-foundations/

## What's in it

- Every definition, worked example and line of arithmetic from Kshitij's original 74 handwritten pages, in the notebook's own order
- 33 hand-drawn diagrams redrawn as clean SVG — projection geometry, hyperplanes, the Argand diagram, descent and feasible-direction cones, epigraphs and convex hulls, PDF/CDF plots, the convolution triangle, the normal curve
- **One interactive figure per week** — twelve plates you drive with sliders and by dragging, each recomputing its own numbers live (see below)
- Mathematics typeset with MathJax
- Sidebar contents with a filter, scroll-linked highlighting, three themes, a reading-progress bar, and print styles

## Interactive figures

Each week opens with a plate you can manipulate. They are drawn from scratch in SVG — no plotting library — and every colour is a CSS custom property, so they follow the theme.

| Week | Figure | What you can do |
|-----:|--------|-----------------|
| 01 | Fitting a line by hand | Drag the data, move \(w\) and \(b\), and compare your loss with the least-squares optimum |
| 02 | Linear and quadratic approximation | Slide the expansion point and read off both approximation errors |
| 03 | Projection onto a line | Drag \(b\) and watch \(e = b - p\) stay perpendicular to the line |
| 04 | Eigenvectors, seen | Set the matrix entries, drag \(x\), and find where \(Ax\) lies along \(x\) |
| 05 | Where the eigenvalues live | Compare unitary, Hermitian and neither in the complex plane |
| 06 | The SVD, geometrically | Watch the unit circle become an ellipse with semi-axes \(\sigma_1, \sigma_2\) |
| 07 | Principal components of a cloud | Change correlation and spread; see the variance PC₁ keeps |
| 08 | Gradient descent, step by step | Click a starting point; cross \(\eta = 2/\lambda_{\max}\) and watch it diverge |
| 09 | The Lagrange condition | Move along the constraint curve until \(\nabla f\) and \(\nabla g\) align |
| 10 | Weak duality and the gap | Slide \(\lambda\) and watch the dual bound close on \(p^\ast\) |
| 11 | Density and distribution | Drag the interval; the area under the PDF matches the rise on the CDF |
| 12 | The bivariate normal | Tilt the contour ellipses with \(\sigma_1, \sigma_2, \rho\) |

## Themes

Three of them — **Paper** (the notebook's own off-white), **Bright** (a high-key violet-and-magenta reading mode) and **Dark** — in the sidebar, or press <kbd>t</kbd> to cycle. Your choice is remembered. Press <kbd>/</kbd> to jump to the contents filter.

## Contents

| Week | Topic |
|-----:|-------|
| 01 | Learning problems — regression, classification, dimensionality reduction, density estimation |
| 02 | Calculus for machine learning — metric spaces, continuity, linear and quadratic approximation, gradients |
| 03 | Four fundamental subspaces and projections; least squares |
| 04 | Regression, eigenvalues and diagonalization |
| 05 | Complex matrices — Hermitian, unitary, Schur's theorem, spectral theorem |
| 06 | Singular value decomposition and positive definiteness |
| 07 | Principal component analysis |
| 08 | Unconstrained optimization and gradient descent |
| 09 | Constrained optimization and convexity |
| 10 | Convexity, duality and the KKT conditions |
| 11 | Continuous random variables |
| 12 | The multivariate normal |

## Building

There is no build step. `index.html` is a single self-contained file; MathJax and the web fonts load from a CDN. Open it directly, or serve the folder with any static host.

## Note

These are personal study notes for the Machine Learning Foundations course in the IIT Madras BS in Data Science and Applications programme. They are not official course material and are not affiliated with or endorsed by IIT Madras or the course instructors.

Notes by **Kshitij Maheshwari** (author). Typeset edition created by **Ammar Hashmi** (creator).
