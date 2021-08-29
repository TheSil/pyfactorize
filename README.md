# factorint
Python integer factorization library. Intended mainly for my personal study of factorization algorithms (for now).

Only simplest, naive algorithms implemented for now:
- factoring by small primes
- wheel factorization (modified trial division)
- pollard rho factorization

Example:

```Python
from factorint import factor
factor.factor(123456789)
```

Output:
```Python
[3^2, 3607, 3803]
```


TODO - Python:
- update to structure to importable/installable package
- argparse for factor cli
- add tests
- formalize configurable parameters for each algorithm

TODO - algorithms:
- Baillie–PSW primality test for probable prime testing (faster than trying to factor)
- Continued fraction factorization
- Quadratic sieve factorization
- Number Field sieve factorization
