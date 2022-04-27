---
title:  "Bernoulli-Euler Beam Theory"
layout: post
usemath: true
typora-root-url: ../
---
Bernoulli-Euler beam theory is the most common theory used to analyze straight beams. In this theory, the transverse shear strain is neglected, making the beam infinitely rigid in the transverse direction. Straight lines perpendicular to the beam axis before deformation remain (a) straight, (b) inextensible, and (c) perpendicular to the tangent line to the beam axis after deformation.

![beam](/assets/images/beam.svg)

The Euler-Bernoulli assumptions lead to the following displacement field:

$$
u(x,y,z)=u(x)-z\frac{dw}{dx}\\
v(x,y,z)=0\\
w(x,y,z)=w(x)
$$

Where $$(u,v,w)$$ are the displacements of a point in the $$(x,y,z)$$ directions respectively. And the infinitesimal strains are:


$$
\epsilon_{xx}=\frac{\partial{u}}{\partial{x}}=\frac{du}{dx}-z\frac{d^2w}{dx^2}\\
\epsilon_{yy}=\frac{\partial{v}}{\partial{y}}=0\\
\epsilon_{zz}=\frac{\partial{w}}{\partial{z}}=0\\
\epsilon_{xy}=\frac{1}{2}\left(\frac{\partial{u}}{\partial{y}} + \frac{\partial{v}}{\partial{x}} \right)=0\\
\epsilon_{xz}=\frac{1}{2}\left(\frac{\partial{u}}{\partial{z}} + \frac{\partial{w}}{\partial{x}} \right) = \frac{1}{2}\left(-\frac{dw}{dx}+\frac{dw}{dx}\right) = 0\\
\epsilon_{yz}=\frac{1}{2}\left(\frac{\partial{v}}{\partial{z}} + \frac{\partial{w}}{\partial{y}} \right)=0\\
$$

All components of the strain tensor vanish except for $$\epsilon_{xx}$$. 
