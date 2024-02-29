# Continued-Fractions-and-Quadratic-Forms-A-Novel-Factorization-Method
In this repository, I publish the code of the factorization algorithm designed in my master thesis. 
This algorithm leverage the properties of continued fractions and quadratic forms.
It has as starting point recent works of Michele Elia, who revisited the fundamental concepts of SQUFOF, including reduced quadratic forms, distance between quadratic forms, and Gauss composition.
## Input
- $N$, the integer to be factored, with the following features:
  - $N>0$, odd, square-free;
  - the period of the continued fraction expansion of $\sqrt{N}$ is even.
- $R$, the regulator of the real quadratic field $\mathbb{Q}(\sqrt{N})$. I point out the fact that $R=\ln (x + y \sqrt{N})$, where (x,y) is the minimal solution of the Pell's Equation $X^2 - NY^2=1$.
## Output
- A nontrivial factor of $N$, smaller than $\sqrt{N}$.
