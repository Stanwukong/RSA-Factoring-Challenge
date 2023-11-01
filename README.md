# RSA-Factoring-Challenge

The RSA Factoring Challenge was a challenge put forward by RSA Laboratories on March 18, 1991 to encourage research into computational number theory and the practical difficulty of factoring large integers and cracking RSA keys used in cryptography. This repo contains code that factorizes numbers into two smaller prime numbers.

## The mathematics
RSA Laboratories states that: for each RSA number _n_, there exist prime numbers _p_ and _q_ such that:
```
n = p * q
```
The problem is to find these two primes, given only _n_
