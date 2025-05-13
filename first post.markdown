---
layout: post
title: my first post
permalink: /about/post1
---

- #self_learning
- [[Self Study Index]]
- Date: 2025-03-27
___
## Introduction
So we know what happens when we have a function with a single variable, for example consider:$$f(x)=y$$This tells us that an input of $x$ will give us the output $y$. 

But what happens when we have a system where there are two variables that produces a single output? Consider:$$f(x,y)=z$$Where $x$ and $y$ is our two inputs and we are given $z$ as a single output.

In this instance, we break way from single variable mathematics and go straight to multivariable mathematics!

## Number types
If we assume $x$ to be a number, we have to precisely define what a number is so that we can find out what we're allowed to do with $x$. From here, we focus on the different categories of numbers:

| Symbol       | Categories      | Includes                                                 |
| ------------ | --------------- | -------------------------------------------------------- |
| $\mathbb{N}$ | Natural numbers | $1, 2, 3, \dots$                                         |
| $\mathbb{Z}$ | Integers        | $\dots, -2, -1, 0, 1, 2, \dots$                          |
| $\mathbb{Q}$ | Rationals       | Fractions; $\frac{n}{d}$                                 |
| $\mathbb{R}$ | Real numbers    | All decimals, finite or infinite, rational or irrational |
| $\mathbb{C}$ | Complex numbers | Numbers such as $2+3i$                                   |
If $x$ is to be an element of one of these categories, we write it as:$$x \in \mathbb{R}$$which tells us that $x$ is a real number.

But why does this matter? The main reason is that once we get into multivariable mathematics, we want to focus on numbers that correspond directly to measurable quantities

if $x$ was an element of a complex number that cannot exist, then we would notate it as:$$x \in \mathbb{C} \text{\\}\mathbb{R}$$


$$f: \mathbb{R}^2 \to\mathbb{R} \text{ where }(x,y) \in \mathbb{R}^2$$
In English: $f$ is a function that takes two real number inputs, $x,y$ and returns a single real number as an output. So:
$\mathbb{R}^2$ = domain of the function, its the 2D real plane
$\mathbb{R}$ = codomain, it represents the output as a single real number
$(x,y) \in \mathbb{R}^2$ specifically states that the input is a point in the 2D plane $\mathbb{R}^2$