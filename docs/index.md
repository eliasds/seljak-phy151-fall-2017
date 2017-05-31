**University of California, Berkeley, Department of Physics**

**PHY151: Fall 2017**

Numerical methods, data science and statistics for physical sciences
====================================================================

Instructor: Uro&#353; Seljak, Campbell Hall 359, useljak@berkeley.edu

Tuesday, Thursday 9:30-11 AM, 325 LeConte Hall

Class Number: 46359

Course Syllabus
---------------

**Learning goals**:
The goals of the course is to get acquainted with modern computational methods
used in physical sciences, including numerical analysis methods, data science and statistics. 
We will introduce a number of concepts that are useful in physical sciences at varying depth levels. We will cover main numerical methods used in physical sciences. Most of the statistical concepts will be Bayesian, 
emphasizing the concepts that have a connection to physical sciences, such as classical and statistical mechanics. We will focus on data science and data analysis concepts that are often encountered in real world physical science applications. 

**Target audience**:
target student population are upper division undergraduates from physical science departments, as well as beginning graduate students from the same departments.

**Course structure**:
each week there will be a set of 3 hour lectures discussing theoretical and practical underpinnings of the specific topic,
together with its most common applications in physical sciences. This will be followed by a weekly python based homework assignment,
applying a subset of the methods to physical science based applications. There will be a one hour discussion of the lecture material and homeworks.

**Prerequsites**:
Undergraduate students: PHY7 or PHY5 series, 
basic introduction to Python programming at the level of PHY77 or permission from instructor. 
Some knowledge of analytic mechanics and statistical physics at the level of PHY105 and PHY112 will be assumed. Graduate students: equivalent of PHY105 and 112, and basic introduction to Python programming, or permission from instructor. 

**Grades**: 30% final project, 70% homeworks.

Weekly Syllabus
---------------

**Function integration**: trapezoidal, Simpson, Romberg, gaussian quadratures

**Special functions, function evaluations and derivatives**: series, recurrence relations, derivatives, Gamma, Bessel, spherical harmonics

**Linear algebra and eigensystems**: Gauss elimination, LU and Cholesky decomposition, singular value decomposition, sparse algebra, matrix diagonalization, principal component analysis

**Nonlinear sets of equations and root finding**: relaxation, bisection, Newton's method

**Optimization (minimization/maximization)**: (stochastic) gradient descent, conjugate gradient (with 
preconditioner), Newton and quasi-Newton (BFGS)

**Interpolation and extrapolation of data**: Polynomial, rational and spline interpolation, gaussian processes

**Fourier transforms**: FFT, convolutions, power spectrum and correlation function, optimal (Wiener) filtering, wavelets

**Ordinary differential equations**: Euler, Runge Kutta, Bulirsch-Stoer, stiff equation solvers, leap-frog and symplectic integrators

**Partial differential equations**: boundary value and initial value problems

**Statistics**: Bayesian inference, priors and posteriors, maximum likelihood and maximum a posterior, linear and
nonlinear model fitting of data, regularization, hierarchical models, probabilistic graphical models

**Information theory, experiment design and error estimation**: Fisher information matrix, (Shannon information) entropy, 
analytic covariance matrix, Monte Carlo simulations, jackknife, bootstrap

**Random processes and Bayesian statistics**: random number generators, Monte Carlo integration with random and sub-random sequences,
Metropolis-Hastings algorithm, Markov Chain Monte Carlo, Gibbs sampling, importance sampling, Hamiltonian Monte Carlo, simulated annealing

**Classification and inference with machine learning and Bayesian Statistics**: Gaussian mixtures with expectation
maximization algorithm, Decision Tree-Based methods, Support Vector Machines, backpropagation neural network algorithms

**Other topics**: symbolic algebra with sympy or mathematica, sorting and neighbor finding, latex with Overleaf, version control with git(hub), debugging with pdb, presentations with powerpoint or keynote.

Literature
----------

- [Numerical Recipes](http://numerical.recipes), by Press. W. etal

- [Information Theory, Inference and Learning Algorithms](http://www.inference.phy.cam.ac.uk/mackay/itila/book.html), by David MacKay,

- [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Sixth%20Printing.pdf), by James G. etal, 

- [A Survey of Computational Physics](http://www.compadre.org/psrc/items/detail.cfm?ID=11578) by Landau, R., Paez, M-J., Bordeianu, C.

- <http://greenteapress.com/wp/think-bayes/>

- <https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers>

- Computational Physics by Mark Newman

- Effective Computation in Physics, by A. Scopatz and K. D. Huff

[//]: # (THESE WERE COMMENTED OUT )

[//]: # (opinionated lectures in statistics by Press W., )

[//]: # (http://wpressutexas.net/coursewiki/index.php/OpinionatedLessons.org/ )

[//]: # (mathematicalmonk series of videos by Jeff Miller, https://www.youtube.com/user/mathematicalmonk/playlists?spfreload=10 )

[//]: # (Various other resources )

[//]: # (https://arxiv.org/pdf/1505.02965.pdf)

[//]: # (https://arxiv.org/abs/1701.02434)

Other resources will be provided according to the needs.

Software
--------

We will use Python Jupyter hub environment. You are expected to use existing numerical analysis routines and not write your own. Many of these are already
implemented in python libraries (scipy, numpy...), or you can call Numerical Recipes C++ routines (as well as other
routines) from python (see <http://numerical.recipes> for details). 

[//]: # (Routines that go with Landau's book are at)
[//]: # (http://www.science.oregonstate.edu/~landaur/Books/CPbook/Codes/PythonCodes/)

Homeworks and Final Exam
------------------------

weekly homeworks, Jupyter notebook in Python submissions. 
Throughout the course, students will complete and electronically submit one homework assignment (code) per week. This code will be run on test cases to check if it produces appropriate results. The GSI will also examine code for proper commenting and style. If the code does not produce appropriate results from the test cases, GSIs will also check for errors to award partial credit for students’ efforts. These manual examinations for errors may be more or less thorough depending on enrollment and availability of the GSI. 
There will be a take home final exam covering the last few weeks of lectures, following the same structure as the homeworks. Take home exam may differ between undergraduate and graduate students. 
