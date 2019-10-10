# Sieve of Eratosthenes
Have you had those moments where you sat back and wondered, "If I had a gun to my head and the only way that I could
was to calculate the sum of all primes below 2 million, how I would I do it?"

Fear not (if you have a laptop with python installed). This repo has you covered.

The jupyter notebook implements the basic Sieve of Eratosthenes algorithm to get all the primes below a certain number and then
simply sums it up. Doing it in a straghtforward manner would've been slow, so I use numba to jit compile the code and then
run it with maximum speed.
