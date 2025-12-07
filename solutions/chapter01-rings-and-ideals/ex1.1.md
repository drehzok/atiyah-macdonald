# Exercise 1.1 — Reference

Book: *Introduction to Commutative Algebra*, Atiyah & MacDonald  
Edition: Special Indian Edition (CRC Press)  
Location: Chapter 1, Exercise 1

---

## My Solution

A nilpotent element is an element $x\in A$ such that $x^n=0$ for some $n>0$. So we want to find $y$ such that (1+x)y = 1. Let's recall from high school the fact that $(1-x)(1+x) = 1-x^2$, then we can easily "cook up" y through $(1+x)(1-x)(1+x^2)(1+x^4)(1+x^8)...(1+x^k) = 1-x^{2k}$, we just choose k such that $2k>n$ then we indeed found $y=(1-x)(1+x^2)...(1+x^k)$ satisfying $(1+x)y = 1$ so $1+x$ is a unit.

A generalisation to the sum of a unit and nilpotent can be done similarly. Let $u$ be a unit (and $v$ be such that $uv=1$) and $n$ be a nilpotent element, then we can perform a simlar operation as above to get $u^{2k}-n^{2k}$ if k is big enough, $u^{2k}-n^{2k}=u^{2k}$, which is a unit because $u^{2k}v^{2k}=1$.

---

Notes

Very straightforward exercise, just tests your knowledge of the definitions involved.


**Status:** Completed

