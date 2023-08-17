---
title: Of Average and Marginal Costs
subtitle: ""
date: 2023-08-10T11:43:33.150Z
summary: ""
draft: false
featured: false
authors:
  - admin
lastmod: 2020-12-13T00:00:00.000Z
tags:
  - costs
  - microeconomics
categories:
  - costs
  - microeconomics
projects: []
image:
  caption: ""
  focal_point: ""
  placement: 2
  preview_only: false
  filename:
---


> Anything that just costs money is cheap.</p>
> — <cite>John Steinbeck</cite>

This is my first blog post ever, so the aim is just to play around and get familiar with this piece of software in general and the type-setting environment for mathematical formulas and equations in particular. As a first topic, I wanted to write a bit about a fundamental concept from microeconomics: the relationship between average and marginal costs. When do marginal costs exceed average costs? When do average costs exceed marginal costs? And where do average costs have their minimum?
As we will see, average costs are always minimised when they equal marginal costs. But here comes the proof...

Let us start with a general cost function $C(q)$, in which costs depend on the quantity produced $q$. Obviously, if we divide by $q$ we get average costs, i.e.
$$
AC=\frac{C}{q}.
$$
Likewise, if we take the first-order derivative, we get marginal costs or
$$
MC=\frac{\partial C}{\partial q}.
$$
But for which quantity produced are average costs decreasing? For which quantities are average costs increasing? Or put differently, for which quantity $q$ are average costs actually minimised? The answer is quite simple and straightforward: average costs are increasing if the first-order derivative for a particular quantity $q$ is positive and they are decreasing if the first-order derivative is negative. Needless to say, that the necessary condition for average costs to be minimised is given by the first-order derivative to equal zero.

So before we start, let us have a quick repetition on the quotient rule for taking derivatives, which states that if we have a nested function
$$
f(x)=\frac{g(x)}{h(x)}
$$
the derivative of $f(x)$ will be given as
$$
\frac{\partial f}{\partial x}=\frac{\frac{\partial h(x)}{\partial x}g(x)-\frac{\partial g(x)}{\partial x}h(x)}{g(x)^2}
$$
Accordingly, we can rewrite and decompose the first-order derivative of average costs as follows
$$
\begin{split}
\frac{\partial AC}{\partial q}&=\frac{\partial \frac{C(q)}{q}}{\partial q}=\frac{\frac{\partial C}{\partial q}q-C}{q^2}\\
&=\frac{1}{q}\left(\frac{\partial C}{\partial q}-\frac{C}{q}\right)\\
&=\frac{1}{q}(MC-AC).
\end{split}
$$

Since quantities $q$ can only take on positive values, it becomes obvious from the last line that
$$
\frac{\partial AC}{\partial q}>0 \quad \text{if }MC>AC
$$
