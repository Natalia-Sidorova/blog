---
title: Scientific programming languages
subtitle: Welcome 👋 Today we will learn scientific programming languages.

# Summary for listings and search engines
summary: Here you can find basic information about scientific programming languages.
# Link this post with a project
projects: []

# Date published
date: '2023-05-06T00:00:00Z'

# Date updated
lastmod: '2023-05-06T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [Programming](https://naked-science.ru/wp-content/uploads/2016/08/field_image_computer-programming_0.jpeg)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Scientific programming languages
  

categories:
  - Programming languages
  
---


## Scientific programming languages

In computer programming, scientific programming language can refer to two degrees of the same concept.

In a broad sense, a scientific programming language is a programming language that is widely used in computational science and computational mathematics. In this sense, C/C++ and Python can be considered as scientific programming languages.

More broadly, a scientific programming language is a language that is designed and optimized for the use of mathematical formulas and matrices. Such languages ​​are characterized not only by the presence of libraries that perform mathematical or scientific functions, but also by the syntax of the language itself. For example, neither C++ nor Python have built-in matrix types or functions for matrix arithmetic (addition, multiplication, etc.); instead, this function is available through the standard libraries. Scientific programming languages ​​in a stricter sense include ALGOL, APL, Fortran, J, Julia, Maple, MATLAB, and R.

Scientific programming languages ​​should not be confused with scientific language in general, which is loose to the higher standards of precision, correctness, and brevity expected of practitioners of the scientific method.

## Examples

1. Linear algebra
Scientific programming languages ​​provide facilities for working with linear algebra. Dealing with large vectors and matrices is a key feature of these languages, as linear algebra lays the foundation for mathematical optimization, which in turn enables mainstream applications such as deep learning.

2. Mathematical optimization
In a scientific programming language, we can calculate the optimum of a function with a syntax close to that of a mathematical language. This example uses Newton's minimization method. Modern scientific programming languages ​​will use automatic differentiation to compute the gradients and hessians of a function given as input; cf. differentiable programming. Here, automatic direct differentiation is chosen for this problem. Old scientific programming languages, such as the venerable Fortran, required the programmer to pass, next to the function to be optimized, a function that calculates the gradient and a function that calculates the Hessian.
The more knowledge about the function to be minimized, the more efficient algorithms can be used. For example, convex optimization provides faster calculations when the function is convex, quadratic programming provides faster calculations when the function is at most quadratic in its variables, and linear programming when the function is as linear as possible.
