# 1.1 A Short Note on Proofs

A mathematical proof is a sequence of statements, each justified by a definition, an assumption, or a result established earlier. A good proof tells the reader why the conclusion follows.

## Direct proof

**Proposition.** If $n$ is an even integer, then $n^2$ is even.

*Proof.* Since $n$ is even, write $n=2k$ for some integer $k$. Then

$$
n^2 = (2k)^2 = 2(2k^2),
$$

so $n^2$ is even. $\square$

## Quantifiers

The order of quantifiers matters. For instance, the statement

$$
\forall x \in \mathbb{R}\; \exists y \in \mathbb{R}: x+y=0
$$

asserts that every real number has an additive inverse.
