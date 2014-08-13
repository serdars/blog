---
title: Example Entry
date: 2014-08-13 07:22 UTC
tags: dream, story
---
Public-key cryptography is based on the intractability of certain mathematical problems. Early public-key systems are secure assuming that it is difficult to factor a large integer composed of two or more large prime factors. For elliptic-curve-based protocols, it is assumed that finding the discrete logarithm of a random elliptic curve element with respect to a publicly known base point is infeasible — this is the "elliptic curve discrete logarithm problem" or ECDLP. The entire security of ECC depends on the ability to compute a point multiplication and the inability to compute the multiplicand given the original and product points. The size of the elliptic curve determines the difficulty of the problem.

READMORE

The primary benefit promised by ECC is a smaller key size, reducing storage and transmission requirements, i.e. that an elliptic curve group could provide the same level of security afforded by an RSA-based system with a large modulus and correspondingly larger key – e.g., a 256-bit ECC public key should provide comparable security to a 3072-bit RSA public key (see key sizes below).

For current cryptographic purposes, an elliptic curve is a plane curve over a finite field (rather than the real numbers) which consists of the points satisfying the equation

y^2 = x^3 + ax + b, \,

along with a distinguished point at infinity, denoted ∞. (The coordinates here are to be chosen from a fixed finite field of characteristic not equal to 2 or 3, or the curve equation will be somewhat more complicated.)

This set together with the group operation of the elliptic group theory form an Abelian group, with the point at infinity as identity element. The structure of the group is inherited from the divisor group of the underlying algebraic variety. As for other popular public key cryptosystems, no mathematical proof of security has been published for ECC as of 2009.

The U.S. National Institute of Standards and Technology (NIST) has endorsed ECC by including schemes based on ECC in its Suite B set of recommended algorithms and allows their use for protecting information classified up to top secret with 384-bit keys.[year needed][3]

```
def my_method
  puts "YAY"
end
```

While the RSA patent expired in 2000, there may be patents in force covering certain aspects of ECC technology, though some (including RSA Laboratories[4] and Daniel J. Bernstein[5]) argue that the Federal elliptic curve digital signature standard (ECDSA; NIST FIPS 186-3) and certain practical ECC-based key exchange schemes (including ECDH) can be implemented without infringing them.
