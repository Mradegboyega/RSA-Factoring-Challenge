RSA Factoring Challenge

This project is a solution to the RSA Factoring Challenge, where the goal is to factorize large numbers into their prime components. RSA Laboratories states that for each RSA number n, there exist prime numbers p and q such that n = p × q. The challenge is to find these two primes given only n.
Task 1 - Prime Factorization
Overview

The program takes a file containing a list of RSA numbers and factors each number into its prime components. Each line in the file contains a single RSA number. The result is printed in the format n = p * q.
Usage

bash

./factors <file>

    <file>: A file containing RSA numbers, one per line.

Example

bash

./factors tests/test00

Requirements

    The program is written in Python 3.
    It uses basic trial division for prime factorization.
    The script assumes that the input numbers have only one prime factorization.

Performance

The performance of the script is limited by the efficiency of the trial division method. For very large RSA numbers, more advanced factorization algorithms like Pollard's rho or the General Number Field Sieve (GNFS) are recommended.
Task 0 - General Factorization

If you are interested in a more general factorization where p and q don't have to be prime numbers, you can refer to the README in the task 0 directory.
Notes

    This is a basic implementation for educational purposes. For practical use and larger RSA numbers, consider using more advanced factorization algorithms.
