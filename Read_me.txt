Code to accompany: Chapter 3 in Thesis "Quantum advantages in unitary gates learning" Mo, yIN

All codes are written in MATLAB and require:

CVX - a Matlab-based convex modeling framework
The functions of QETLAB is also used: see folder "QETLAB_used_functions".
Two functions provided by Marco Túlio Quintino from "https://github.com/mtcq/unitary_inverse" are also used, see folder "From_Marco_functions"

It has been tested on Matlab R2019b, and CVX 2.1 

The main purpose of these codes:

1. zip 'learning_probabilistic_1.zip': files in this folder solve the problem of probabilistic unitary gates learning, 
and get the optimal learning probability when noisy gate is the completely depolarizing channle.

2. zip 'learning_probabilistic_2.zip': files in this folder solve the problem of probabilistic unitary gates learning, 
and get the optimal learning probability when noisy gate is a unitary gate mixed with the completely depolarizing channle, 
with some probability.

3. zip 'learning_deterministic_primal.zip': files in this folder solve the problem of deterministic unitary gates learning, 
and get a lowerboud of the learning fidelity when noisy gate is the completely depolarizing channle.

4. zip 'learning_deterministic_dual.zip': files in this folder solve the problem of deterministic unitary gates learning, 
and get an upperboud of the learning fidelity when noisy gate is the completely depolarizing channle.

To use these codes, only file "learning_run_xxx" is needed to be used.