---
title: Another Example Entry
date: 2014-08-13 07:22 UTC
tags: code, dream
---

For the one-time pad system the key must be at least as long as the message. In encryption systems that use a cipher algorithm, messages can be much longer than the key. The key must, however, be long enough so that an attacker cannot try all possible combinations.

A key length of 80 bits is generally considered the minimum for strong security with symmetric encryption algorithms. 128-bit keys are commonly used and considered very strong. See the key size article for a more complete discussion.

READMORE

## More information

The keys used in public key cryptography have some mathematical structure. For example, public keys used in the RSA system are the product of two prime numbers. Thus public key systems require longer key lengths than symmetric systems for an equivalent level of security. 3072 bits is the suggested key length for systems based on factoring and integer discrete logarithms which aim to have security equivalent to a 128 bit symmetric cipher. Elliptic curve cryptography may allow smaller-size keys for equivalent security, but these algorithms have only been known for a relatively short time and current estimates of the difficulty of searching for their keys may not survive. As of 2004, a message encrypted using a 109-bit key elliptic curve algorithm had been broken by brute force.[2] The current rule of thumb is to use an ECC key twice as long as the symmetric key security level desired. Except for the random one-time pad, the security of these systems has not (as of 2008) been proven mathematically, so a theoretical breakthrough could make everything one has encrypted an open book. This is another reason to err on the side of choosing longer keys.
