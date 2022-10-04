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
    - [Posits, discussed by John Cook](https://www.johndcook.com/blog/2018/04/11/anatomy-of-a-posit-number/)
  - [Avoiding catastrophic cancellation with quadratic formula](https://www.cs.utexas.edu/users/flame/laff/alaff/a2appendix-catastrophic-cancellation.html)
  - [Lecture notes from Richard Krueger of UT](http://www.cs.toronto.edu/~krueger/csc165h/f06/lectures/ch7.pdf) 
  - [What Every Computer Scientist Should Know About Floating-Point Arithmetic by David Goldberg](https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)
  
## Linear systems

  - [Overview of solving linear systems from Chen Greif](https://www.cs.tau.ac.il/~dcor/Graphics/adv-slides/Solving.pdf)
  - Don't invert that matrix!
    - [Greg Gundersen](https://gregorygundersen.com/blog/2020/12/09/matrix-inversion/)
    - [John Cook](https://www.johndcook.com/blog/2010/01/19/dont-invert-that-matrix/)
    - [SciComp StackExchange Q/A](https://scicomp.stackexchange.com/questions/26423/practical-example-of-why-it-is-not-good-to-invert-a-matrix)
  - Direct linear solvers 
    - [John Foster (video)](https://www.youtube.com/watch?v=9Brr6fzDb-o) and [accompanying notes](https://johnfoster.pge.utexas.edu/numerical-methods-book/LinearAlgebra_DirectSolvers.html)
    - LU Decomposition 
      - [thenumericalmethodsguy (videos)](https://nm.mathforcollege.com/chapter-04-07-lu-decomposition-method/)
      - [Lecture notes from CCNY Math](https://math.sci.ccny.cuny.edu/document/328Ch5)
  - Using linear solvers to benchmark supercomputers 
    - [Vanilla linpack discussion](https://www.top500.org/project/linpack/)
    - [High performance linpack (HPL)](https://netlib.org/benchmark/hpl/)

## Least squares 

  - [Steve Brunton on linear systems, least squares, and more (video)](https://www.youtube.com/watch?v=PjeOmOz9jSY)
  - [Strang on four ways to solve least squares problems (video)](https://www.youtube.com/watch?v=ZUU57Q3CFOU)
  - QR and its flavors
    - [Least Squares via QR with John Lambert](https://johnwlambert.github.io/least-squares/)
    - [Gil Strang on Gram-Schmidt (video)](https://www.youtube.com/watch?v=0MtwqhIwdrI)
    - [Gram-Schmidt and loss of orthogonality](https://www.cis.upenn.edu/~cis6100/Gram-Schmidt-Bjorck.pdf) 
    - [Blog on QR from TDS, Ben Denis Shaffer](https://towardsdatascience.com/qr-matrix-factorization-15bae43a6b2)
    - [Arnold Yim on QR (video)](https://www.youtube.com/watch?v=7KP6TO5JXYY)

## Eigenvalues 

  - Introduction
    - [3Blue1Brown (video)](https://www.3blue1brown.com/lessons/eigenvalues)
    - [Lecture notes from Yin Zhang of Rice](https://www.cmor-faculty.rice.edu/~zhang/caam335/F09/handouts/UH_lecture.pdf)
  - Videos from Prof. Gil Strang (MIT)
    - [Similar matrices (video)](https://www.youtube.com/watch?v=LKMGo8G7-vk)
    - [Symmetric matrices (video)](https://www.youtube.com/watch?v=ZTNniGvY5IQ)
  - [Why we don't use characteristic polynomials to compute eigenvalues in practice, at least for large matrices](https://mathematica.stackexchange.com/questions/20379/eigenvalues-and-determinant-of-a-large-matrix)
    - From Michael Heath's book:
      > Computing the coefficients of the characteristic polynomial for a given matrix is, in general, a substantial task. The coefficients of the characteristic polynomial can be highly sensitive to perturbations in the matrix, and hence their computation is unstable. Rounding error incurred in forming the characteristic polynomial can destroy the accuracy of the roots subsequently computed. Computing the roots of a polynomial of high degree is another substantial task (indeed, one of the better ways of computing the roots of a polynomial is to compute the eigenvalues of its companion matrix using the methods we use for eigenvalues. 
  - Krylov Subspace Methods
    - [Slides from Sanjeev Kumar of UCSD](https://cseweb.ucsd.edu/classes/fa04/cse252c/sakumar.pdf)
    - [Slides from Karl Meerbergen of WSC](https://wsc.project.cwi.nl/woudschoten-conferences/2017-woudschoten-conference/Meerbergenslides1.pdf)
    - [Lecture from Slim Belhaiza of KFUPM (video)](https://www.youtube.com/watch?v=w4pTZjQD4pg)
  - QR for Eigenvalues
    - [Lecture from Martijn Anthonissen of TUe (video)](https://www.youtube.com/watch?v=BfGAmw9qKsM)
    - [Notes from Tin-Yau Tam of Auburn](http://webhome.auburn.edu/~tamtiny/lecture%2011.pdf)
  - Power method (or iteration)
    - [Wikipedia entry](https://en.wikipedia.org/wiki/Power_iteration)
    - Video lecture from Jeffrey Chasnov: [Part 1](https://www.youtube.com/watch?v=_PDyi5BVY-E) and [Part 2](https://www.youtube.com/watch?v=nKd0lu3yThg) 
    - [Lecture from Jacob Bishop (video)](https://www.youtube.com/watch?v=Yhs0Fcpv6y4)
    - [Lecture notes from of Jeffrey Wong of Duke](https://services.math.duke.edu/~jtwong/math361-2019/lectures/Lec10eigenvalues.pdf)

## Numerical time integration 

  - Videos from Prof. Steve Brunton (Washington) 
    - [Introduction to the topic](https://www.youtube.com/watch?v=rdB9vN2YxKs) 
    - [Forward and Backward Euler](https://www.youtube.com/watch?v=zdz1q4tJOmE) 
    - [Runge-Kutta](https://www.youtube.com/watch?v=5CXhHx56COo)
  
  - [David Shirokoff on Euler's method](https://www.youtube.com/watch?v=X5-ucBtneVM)

## Numerical integration and quadrature

  - Gaussian Quadratrue
    - [Jeff Chasnov (video)](https://www.youtube.com/watch?v=w2xjlPwYock)
  
## Ordinary differential equations

  - [3Blue1Brown (video)](https://youtu.be/p_di4Zn4wz4)

## Partial differential equations

  - [3Blue1Brown (video)](https://youtu.be/ly4S0oi3Yz8)
