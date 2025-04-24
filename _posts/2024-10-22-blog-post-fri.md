---
title: 'Practical notes on the FRI low degree test'
date: 2024-10-22
permalink: /posts/2024/10/fri/
tags:
  - cryptography
  - STARKs
  - fri
---

- FRI (Fast-Reed Solomon IOPP) is a protocol that demonstrates proximity for a linear code to a low-degree polynomial.
- FRI is a round-by-round interactive protocol between a prover and a verifier.
- The prover commits to a Reed-Solomon codeword that evaluates to some low-degree polynomial.
- The verifier makes oracle queries to the alleged codeword at random points and verifies that the result matches the given commitment. - If sufficient queries succeed, the verifier is convinced that the committed codeword will pass the low-degree test.

[Link to blogpost](https://hackmd.io/@deanstef/SJTT3MDhC)
