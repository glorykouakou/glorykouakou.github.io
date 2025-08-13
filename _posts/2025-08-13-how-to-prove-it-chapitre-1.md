---
layout: post
title: "My notes on How to Prove It - Chapter 1: Sentencial Logic"
date: 2025-08-14 10:00:00 +0200
categories: [Logic, How to Prove It]
---

### Introduction

In this article, I'm sharing my notes on the foundational concepts from Daniel J. Velleman's *How to Prove It*. I've covered chapters 1 to 3, which lay the groundwork for logic and mathematical proofs.

### Chapter 1: The Language of Mathematics

This chapter introduced the basic building blocks of logic.

* **Logical Connectives:** I focused on "and" ($\land$), "or" ($\lor$), "not" ($\neg$), "if...then" ($\to$) and "if and only if" ($\leftrightarrow$).

* **Truth Tables:** I learned how to construct truth tables for complex logical statements like $(P \land Q) \to R$.

### Chapter 2: The Logic of Quantifiers

This part was about quantifiers, which are crucial for formal proofs.

* **Universal Quantifier:** The symbol $\forall$ ("for all").
* **Existential Quantifier:** The symbol $\exists$ ("there exists").

### Chapter 3: Direct Proof

This is where the theory comes to life. I learned how to build my first direct proofs. For example, to prove that if $n$ is an even integer, then $n^2$ is also an even integer.

**Proof:**
Since $n$ is an even integer, there exists some integer $k$ such that $n = 2k$.
Then $n^2 = (2k)^2 = 4k^2 = 2(2k^2)$.
Since $2k^2$ is an integer, $n^2$ is an even integer.
Q.E.D.

---

### Conclusion

Mastering these concepts is fundamental. Velleman's clarity and rigor are helping me to structure my thinking for future proofs. The next article will cover proofs by contrapositive and contradiction.
