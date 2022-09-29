# Awesome Numerics

Resources for learning about numerical methods.
This document is a work in progress, but nevertheless contains useful information. 
Indended audience has little or modest experience with numerical methods.
Assumed knowledge is an undergraduate linear algebra course and the calculus/diff. equations sequence.
Most linked content is _not_ licensed, owned, or maintained by S. H. Bryngelson.

## Linear algebra refresher 
  - [Gilbert Strang (video)](https://www.youtube.com/playlist?list=PL49CF3715CB9EF31D)
  - [3Blue1Brown (video)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

## Floating point numbers 
  - [Computerphile (video)](https://www.youtube.com/watch?v=PZRI1IfStY0)
  - [IEEE standards (video)](https://www.youtube.com/watch?v=RuKkePyo9zk)
  - [GeeksForGeeks](https://www.geeksforgeeks.org/introduction-of-floating-point-representation/) 
  - Other floating point number formats 
    - [bfloat](https://en.wikipedia.org/wiki/Bfloat16_floating-point_format)
    - [tf32](https://blogs.nvidia.com/blog/2020/05/14/tensorfloat-32-precision-format/)
  - [Avoiding catastrophic cancellation with quadratic formula](https://www.cs.utexas.edu/users/flame/laff/alaff/a2appendix-catastrophic-cancellation.html)
  - [Lecture notes from Richard Krueger of UT](http://www.cs.toronto.edu/~krueger/csc165h/f06/lectures/ch7.pdf) 
  
## Linear systems

  - [Overview of solving linear systems from Chen Greif](https://www.cs.tau.ac.il/~dcor/Graphics/adv-slides/Solving.pdf)
  - Don't invert that matrix!
    - [Greg Gundersen](https://gregorygundersen.com/blog/2020/12/09/matrix-inversion/)
    - [John Cook](https://www.johndcook.com/blog/2010/01/19/dont-invert-that-matrix/)
    - [SciComp StackExchange Q/A](https://scicomp.stackexchange.com/questions/26423/practical-example-of-why-it-is-not-good-to-invert-a-matrix)
  - Direct linear solvers 
    - [John Foster (video)](https://www.youtube.com/watch?v=9Brr6fzDb-o)
    - <https://johnfoster.pge.utexas.edu/numerical-methods-book/LinearAlgebra_DirectSolvers.html>
    - LU Decomp 
      - <https://www.youtube.com/watch?v=dza5JTvMpzk> 
      - <https://www.youtube.com/watch?v=5eBmb8ir-uA>
      - <https://math.sci.ccny.cuny.edu/document/328Ch5>
  - How we use linear solvers to benchmark supercomputers 
    - Vanilla linpack discussion: <https://www.top500.org/project/linpack/>
    - High performance linpack (HPL): <https://netlib.org/benchmark/hpl/> 

## Least squares 

  - [Steve Brunton](https://www.youtube.com/watch?v=PjeOmOz9jSY)
  - [Strang](https://www.youtube.com/watch?v=ZUU57Q3CFOU)
  - <https://johnwlambert.github.io/least-squares/>
  - <https://towardsdatascience.com/qr-matrix-factorization-15bae43a6b2>
  - <https://www.youtube.com/watch?v=7KP6TO5JXYY>
  - <https://www.youtube.com/watch?v=OCLFZwi40nM>
  - Othogonalization 
    - <https://www.youtube.com/watch?v=0MtwqhIwdrI> 
  - Gram-Schmidt and loss of orthogonality: <https://www.cis.upenn.edu/~cis6100/Gram-Schmidt-Bjorck.pdf> 

## Eigenvalues 

  - [SixtySymbols](https://www.youtube.com/watch?v=PFDu9oVAE-g)
  - [Strang (similar matrices)](https://www.youtube.com/watch?v=LKMGo8G7-vk)
  - [Strang](https://www.youtube.com/watch?v=ZTNniGvY5IQ)

## Numerical time integration 

  - Steve Brunton [1](https://www.youtube.com/watch?v=rdB9vN2YxKs) [2](https://www.youtube.com/watch?v=zdz1q4tJOmE) [3](https://www.youtube.com/watch?v=5CXhHx56COo)
  - [Shirokoff](https://www.youtube.com/watch?v=X5-ucBtneVM)

## Numerical integration and quadrature 
  - [Chasnov](https://www.youtube.com/watch?v=w2xjlPwYock)
  
## Differential equations refresher 
  - [3Blue1Brown (ODE)](https://youtu.be/p_di4Zn4wz4)
  - [3Blue1Brown (PDE)](https://youtu.be/ly4S0oi3Yz8)
