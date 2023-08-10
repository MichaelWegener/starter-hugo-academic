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
  caption: "Image credit: [**gerald at
    pixabay**](https://pixabay.com/illustrations/cost-board-finance-money-busin\
    ess-1174926/)"
  focal_point: ""
  placement: 2
  preview_only: false
  filename: cost-1174926_1920-1-.jpg
---


> Anything that just costs money is cheap.</p>
> — <cite>John Steinbeck</cite>

This is my first blog post ever, so the aim is just to play around and get familiar with this piece of software in general and the type-setting environment for mathematical formulas and equations in particular. As a first topic, I wanted to write a bit about a fundamental concept from microeconomics: the relationship between average and marginal costs. When do marginal costs exceed average costs? When do average costs exceed marginal costs? And where do average costs have their minimum?
As we will see, average costs are always minimised when they equal marginal costs. But here comes the proof...
Let us start with a general cost function \(C(q)\), in which costs depend on the quantity produced \(q\). If we divide by \(q\) we get average costs, i.e.
\begin{equation*}
AC=\frac{C}{q}.
\end{equation*}
Likewise, if we take the first-order derivative, we get marginal costs or

{{< /math >}}
\begin{equation*$$
MC=\frac{\partial C}{\partial q}.
$$*

{{< /math >}}

But for which quantity produced are average costs decreasing? For which quantities are average costs increasing? Or put differently, for which quantity $q$ are average costs actually minimised? The answer is quite simple and straightforward: average costs are increasing if the first-order derivative for a particular quantity $q$ is positive and they are decreasing if the first-order derivative is negative. Needless to say, that the necessary condition for average costs to be minimised is given by the first-order derivative to equal zero.

So before we start, let us have a quick repetition on the quotient rule for taking derivatives, which states that if we have a nested function
\begin{equation*}
f(x)=\frac{g(x)}{h(x)}
\end{equation*}
the derivative of \(f(x)\) will be given as
\begin{equation*}
\frac{\partial f}{\partial x}=\frac{\frac{\partial h(x)}{\partial x}g(x)-\frac{\partial g(x)}{\partial x}h(x)}{g(x)^2}
\end{equation*}
Accordingly, we can rewrite and decompose the first-order derivative of average costs as follows
\begin{align*}
\frac{\partial AC}{\partial q}&=\frac{\partial \frac{C(q)}{q}}{\partial q}=\frac{\frac{\partial C}{\partial q}q-C}{q^2}\\\\
&=\frac{1}{q}\left(\frac{\partial C}{\partial q}-\frac{C}{q}\right)\\\\
&=\frac{1}{q}(MC-AC).
\end{align*}
Since quantities \(q\) can only take on positive values, it becomes obvious from the last line that \(\frac{\partial AC}{\partial q}>0\) if \(MC>AC\) and that \(\frac{\partial AC}{\partial q}<0\) if \(MC<AC\). In other words, average costs are increasing if marginal costs exceed average costs and average costs are decreasing if average costs exceed marginal costs. Moreover, if marginal costs equal average costs, average costs are at their minimum.