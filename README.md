# Awesome Numerics

Resources for learning about numerical methods.
This document is a work in progress, but nevertheless contains useful information. 
Indended audience has little or modest experience with numerical methods.
Assumed knowledge is an undergraduate linear algebra course and the calculus/diff. equations sequence.
Most linked content is _not_ licensed, owned, or maintained by S. H. Bryngelson.

## Linear algebra refresher 

Numerical analysis and linear algebra are fundamentally entangled. 
Forget your lin. alg. basics at your own risk. 
Fortunately, there are many great resources to get you up to speed, so dust off your copy of Gil Strang's book and check out the links below.

  - [Gilbert Strang (video)](https://www.youtube.com/playlist?list=PL49CF3715CB9EF31D)
  - [3Blue1Brown (video playlist)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

## Floating point numbers 
  - [Computerphile (video)](https://www.youtube.com/watch?v=PZRI1IfStY0)
  - [IEEE standards (video)](https://www.youtube.com/watch?v=RuKkePyo9zk)
  - [GeeksForGeeks](https://www.geeksforgeeks.org/introduction-of-floating-point-representation/) 
  - Other floating point number formats 
    - [Google bfloat](https://en.wikipedia.org/wiki/Bfloat16_floating-point_format)
    - [NVIDIA tf32](https://blogs.nvidia.com/blog/2020/05/14/tensorfloat-32-precision-format/)
    - [Tesla cfloat](https://tesla-cdn.thron.com/static/SBY4B9_tesla-dojo-technology_OPNZ0M.pdf?xseo=&response-content-disposition=inline%3Bfilename%3D%22tesla-dojo-technology.pdf%22)
    - [Posits discussed John Cook](https://www.johndcook.com/blog/2018/04/11/anatomy-of-a-posit-number/)
  - [Avoiding catastrophic cancellation with quadratic formula](https://www.cs.utexas.edu/users/flame/laff/alaff/a2appendix-catastrophic-cancellation.html)
  - [Lecture notes from Richard Krueger of UT](http://www.cs.toronto.edu/~krueger/csc165h/f06/lectures/ch7.pdf) 
  
## Linear systems

  - [Overview of solving linear systems from Chen Greif](https://www.cs.tau.ac.il/~dcor/Graphics/adv-slides/Solving.pdf)
  - Don't invert that matrix!
    - [Greg Gundersen](https://gregorygundersen.com/blog/2020/12/09/matrix-inversion/)
    - [John Cook](https://www.johndcook.com/blog/2010/01/19/dont-invert-that-matrix/)
    - [SciComp StackExchange Q/A](https://scicomp.stackexchange.com/questions/26423/practical-example-of-why-it-is-not-good-to-invert-a-matrix)
  - Direct linear solvers 
    - [John Foster (video)](https://www.youtube.com/watch?v=9Brr6fzDb-o) and [accompanying notes](https://johnfoster.pge.utexas.edu/numerical-methods-book/LinearAlgebra_DirectSolvers.html)
    - LU Decomposition 
      - <https://www.youtube.com/watch?v=dza5JTvMpzk> 
      - <https://www.youtube.com/watch?v=5eBmb8ir-uA>
      - <https://math.sci.ccny.cuny.edu/document/328Ch5>
  - Using linear solvers to benchmark supercomputers 
    - [Vanilla linpack discussion](https://www.top500.org/project/linpack/)
    - [High performance linpack (HPL)](https://netlib.org/benchmark/hpl/)

## Least squares 

  - [Steve Brunton](https://www.youtube.com/watch?v=PjeOmOz9jSY)
  - [Strang](https://www.youtube.com/watch?v=ZUU57Q3CFOU)
  - <https://johnwlambert.github.io/least-squares/>
  - <https://towardsdatascience.com/qr-matrix-factorization-15bae43a6b2>
  - <https://www.youtube.com/watch?v=7KP6TO5JXYY>
  - <https://www.youtube.com/watch?v=OCLFZwi40nM>
  - Othogonalization 
    - <https://www.youtube.com/watch?v=0MtwqhIwdrI> 
  - [Gram-Schmidt and loss of orthogonality](https://www.cis.upenn.edu/~cis6100/Gram-Schmidt-Bjorck.pdf) 

## Eigenvalues 

  - Introduction
    - [3Blue1Brown (video)](https://www.3blue1brown.com/lessons/eigenvalues)
    - [Lecture notes from Yin Zhang of Rice](https://www.cmor-faculty.rice.edu/~zhang/caam335/F09/handouts/UH_lecture.pdf)
  - Videos from Prof. Gil Strang (MIT)
    - [Strang (similar matrices, video)](https://www.youtube.com/watch?v=LKMGo8G7-vk)
    - [Strang (symmetric matrices, video)](https://www.youtube.com/watch?v=ZTNniGvY5IQ)

## Numerical time integration 

  - Videos from Prof. Steve Brunton (Washington) 
    - [Introduction to the topic](https://www.youtube.com/watch?v=rdB9vN2YxKs) 
    - [Forward and Backward Euler](https://www.youtube.com/watch?v=zdz1q4tJOmE) 
    - [Runge-Kutta](https://www.youtube.com/watch?v=5CXhHx56COo)
  
  - [David Shirokoff on Euler's method](https://www.youtube.com/watch?v=X5-ucBtneVM)

## Numerical integration and quadrature

  - [Chasnov](https://www.youtube.com/watch?v=w2xjlPwYock)
  
## Ordinary differential equations

  - [3Blue1Brown (video)](https://youtu.be/p_di4Zn4wz4)

## Partial differential equations

  - [3Blue1Brown (video)](https://youtu.be/ly4S0oi3Yz8)
