---
layout: article
title: "Determination of the greatest height consistent with stability that a vertical pole or mast can be made, and of the greatest height to which a tree of given proportions can grow"
author: [A. G. Greenhill]
year: 1881
container: Proceeding of the Cambridge Philosophical Society
number: vol. 4
page: pp. 65-73
usemath: true
typora-root-url: ../
---

The original article can be found [here](https://books.google.so/books?id=GpI1AAAAIAAJ) in pdf form on Google Books.

***

Suppose a uniform cylindrical pole or wire fixed in a vertical direction at its lowest point, and carried to such a height that the vertical position becomes unstable and flexure begins; it is required to determine this height.

Let $$2a$$ be the diameter in inches, and $$A$$ the sectional area of the pole in square inches: and $$E$$ be Young's modulus of elasticity of the substance, expressed in gravitation measure of lb to the square inch.

Then, if $$\rho$$ be the radius of curvature of the central fiber of the pole, the bending moment of resilience (the unit being the inch-lb)


$$
= EI \frac{1}{\rho}=EAk^3\frac{1}{\rho} \nonumber
$$

Take the origin $$O$$ at the top of the pole in its vertical position and the axis $$Ox$$ directed vertically downwards:  

![beam](/assets/images/self_buckling.svg)

Then if $$APB$$ be the central line of the pole, supposed to be slightly curved under its own weight, we may put $$\frac{1}{\rho}=\frac{dp}{dx}$$, where $$\rho=\frac{dy}{dx}$$, and therefore the bending moment at $$P$$

$$
=EAk^2\frac{dp}{dx} \nonumber
$$

This must be equated to the moment of the weight of $$PB$$ about $$P$$, which


$$
=wA\int\limits_0^x(y'-y)dx' \nonumber
$$

$$x'$$, $$y'$$ denoting the co-ordinates of any point $$Q$$ between $$B$$ and $$P$$, and $$w$$ the density of the substance in pounds to the cubic inch.

Therefor the differential equation of the central line $$APB$$ is


$$
EAk^2\frac{dp}{dx}=wA\int\limits_0^x(y'-y)dx' \nonumber
$$


or, differentiating with respect to $$x$$,


$$
\begin{align}
EAk^2\frac{d^2p}{dx^2} &= -wA\int\limits_0^xpdx' \nonumber \\
& = -wAxp \nonumber \\
x^2\frac{d^2p}{dx^2} &+ \frac{w}{Ek^2}x^2p = 0
\label{eq:1}
\end{align}
$$
