# Proof by Contradiction

- something very simple that we use every day

Ex:
3sqrt 1332 <= 11

This can be proven by simply calculating it, but there is a simpler way:

- if the assumption is true, we'd be able to cube both sides of the equasion,
  meaning that 1332 <= 11 cubed which is much easier to calculate
  - this is of course not true as calculated this is 1332 <= 1331
  - which immediately means we've contradicted our initial assumption and
    at the same time have proven that 1331 > 1332

=> If an assertion implies something false, **then the assertion itself must be false!**

Example:
Theorem: √2 is irrational

In order to prove this by contradiction, we'll assume the opposite and try to prove that instead:

- suppose √2 was rational
  - which means we have n, d integers w/o common prime factors such that:
    √2 = n / d
- we will show that n & d dare both even. This _contradicts_ the no common factor assumption

- start with the assumption:
  √2 = n/d | \*d
  √2d = n | \*\*2
  2 d2 = n2

  So since 2d2 is divisible by 2, n2 has to be to, therefore we can assume that n is even!

- next assumption:
  n = 2k (2 \* whatever pretty much as it is divisible by 2)
  n2 = 4k2
  2d2 = 4k2
  d2 = 2k2

Since d2 is divisible by 2 as well (same assumption as above) we can assume that d is even!

Since both are divisible by 2, they **do** have common prime factors which contradicts
our assumption that √2 is rational!

One assumption we've made here, is that if n2 is even n is even as well

- in order for our proof be spotless, this has to be proven as well!
