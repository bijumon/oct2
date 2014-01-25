---
layout: post
title: "Equations"
date: 2012-08-31 14:34
comments: true
categories: [Math]
tags: [latex, math]
---
The following equations are represented in the HTML source code as LaTeX expressions.

The Lorenz Equations

$$\begin{aligned}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{aligned}$$

The Cauchy-Schwarz Inequality

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

A Cross Product Formula

$$\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0
\end{vmatrix}$$

The probability of getting \(k\) heads when flipping \(n\) coins is

$$P(E) = \left( \binom{n}{k} \right) p^k (1-p)^{ n-k}$$

An Identity of Ramanujan

$$\frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} =
1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}}
{1+\frac{e^{-8\pi}} {1+\ldots} } } }$$

Maxwell’s Equations

$$\begin{aligned}
\nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} & = \frac{4\pi}{c}\vec{\mathbf{j}} \\   \nabla \cdot \vec{\mathbf{E}} & = 4 \pi \rho \\
\nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} & = \vec{\mathbf{0}} \\
\nabla \cdot \vec{\mathbf{B}} & = 0 \end{aligned}$$

Finally, while display equations look good for a page of samples, the ability to mix math and text in a paragraph is also important. This expression $$\sqrt{3x-1}+(1+x)^2$$ is an example of an inline equation.  As you see, MathJax equations can be used this way as well, without unduly disturbing the spacing between lines.
