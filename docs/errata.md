---
layout: page
title: Errata
---
**p. 20 (2019-03-28)**: Caption of Figure 2.3 should say "...is proportional to the number of observed birds..."
  
**p. 38 (2021-04-27)**: The right-hand side of equation (2.8) should be divided by 2.

**p. 52 (2024-05-15):** First sentence begins "As running example..." and should be "As a running example..."

**p. 54 (2019-10-31)**: Second paragraph, last line should start with "precipitation,..."

**p. 71 (2019-09-19)**: Penultimate line should say "...of size 80km"

**Explanatory note for 2020-07-22 errata**: In Ch. 1 &ndash; 3, the intercept variable "1" is listed along with *p* covariates. From Ch. 4 onwards, the intercept is absorbed into the covariate vector, **x**(**s**; *t*), which is specified there to be *p*-dimensional, in line with standard notation for multivariable regression. This leads to a slight abuse of notation and requires the following errata in Ch. 4 &ndash; 5.

**p. 103 (2024-05-15):** In the technical note at the bottom of the page, the sentence "Specifically, suppose we have a model for an *m*-vector..." should read "Specifically, suppose we have a model for an *m*-dimensional vector..."

**p. 109 (2024-05-15):** In the paragraph beginning with "To carry out CV...," the sentence "We denote the sum of the discrepancies..." should say "We denote the mean of the discrepancies ...".

**p. 139 (2020-07-22)**: At the end of Section 4.1, add the sentence: "Note that in this and subsequent chapters, the covariate vector **x**(**s**; *t*) could include the variable "1," which models an intercept in the multivariable regression."

**p. 140, line 22 (2020-07-22)**: Change "(*p* + 1) matrix given by..." to "*p* matrix given by..."

**p. 152, Technical Note 4.2 (2020-07-22)**: Change "...column space of the *m*&times;(*p* + 1) design matrix **X**." to "...column space of the *m*&times;*p* design matrix **X**."

**p. 173 (2024-05-29)**: The last sentence of the page should read "The code returns a plot of the fitted semivariograms. The corresponding S-T covariance function is obtained from (4.15), and the fitted separable and nonseparable covariance models are shown in the bottom panels of Figure 4.4.

**p. 200 (2024-05-15):** The penultimate sentence begins as "The posterior distribution of the marginal variance of the latent field is largest between 2 and 4, These values..." and should have a period between "4" and "These" rather than a comma.

**p. 218 (2024-05-15):** First paragraph of Section 5.3 begins "The latent linear Gaussian DSTM described in Section 5.2 above has unknown parameters associated with the data model Cη, ..." and should say "process model" instead of "data model".
https://www.facebook.com/marketplace/item/760793922557950/
**p. 218 (2024-05-15):** Final paragraph beginning, "Generally, the transition-matrix parameters in the DSTM process model require the most care, as there there could be ...", and one "there" should be removed.

**p. 223, line 3 (2020-07-22)**: Change "...is an *n*&times;(*p* + 1) matrix that could be time-varying..." to "...is an *n*&times;*p* matrix that could be time-varying..."

**p. 226 (2024-05-15):** An example of a GQN DSTM to accompany Equation (5.22) is Hooten and Wikle (2010): <https://doi.org/10.1198/jasa.2009.tm09036>

**p. 269 (2024-05-15):** In the unnumbered equation for a p-value 𝑝<sub>B</sub>, "B" refers to "Bayes".

**p. 277 (2020-12-24)**: On the line directly below (6.23), **Z** should be **Z’**, a row vector.

The following errata resulted from questions asked by Nicholas Antoniou; the authors are grateful for his careful reading of the book.
  
**p. 320 (2020-12-24)**: On the right-hand side of (D.3), the sign in front of "b" should be "+", not "–".

**p. 320 (2020-12-24)**: On the fifth line below (D.4), the vector **Y**<sub>t</sub> should be an n-dimensional vector.
. On the same line, the matrix **cap-phi** should be an n x n<sub>alpha</sub> matrix.

**p. 320 (2020-12-24)**: On the sixth line below (D.4), the vector **alpha**<sub>t</sub> contains the associated n<sub>alpha</sub> expansion coefficients.

**p. 323 (2020-12-24)**: In equations (E.1) and (E.2), delta<sub>t</sub> = 1, and hence "delta<sub>t</sub>" should not appear in these two equations. 
. On the second line below (E.2), "delta<sub>t</sub>" and "time-" should be removed.

**p. 341 (2020-12-24)**: In the first line, the range of t should be 2, ..., T, and the line after (F.8) should read, "where **h**<sub>1</sub> is a specified initial value, **Y**<sub>t</sub> is the n<sub>y</sub>-dimensional response vector... ".
. In equation (F.3), the vector **h**<sub>t</sub><sup>2</sup> is defined elementwise, and hence it has the same dimension as the vector **h**<sub>t</sub>; that is, both vectors are n<sub>h</sub>-dimensional.
. On the fourth line below (F.9), remove "As in the basic ESN above," and start the sentence as follows: "The matrix **W** is the n<sub>h</sub> x n<sub>h</sub> hidden-process-evolution weight matrix, ..."
. On the fifth line below (F.9), the matrix **U** should be an n<sub>h</sub> x n<sub>x-tilde</sub> matrix.
. On the fifth and sixth lines below (F.9), the matrices **V**<sub>1</sub> and **V**<sub>2</sub> should both be n<sub>y</sub> x n<sub>h</sub> matrices.

**p. 342 (2020-12-24)**: In the box showing **Algorithm F.1**, the step "2." should carry out the calculation (using (F.4)) from t = 2, ..., T.
