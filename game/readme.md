## No best policy in n

**You can’t see the forest for the trees**

The global optimal solution and the local optimal solution are relative.

A local optimum can only approach the global optimum.

Due to (n + 1)-dimensional interference and incomplete modeling, the global optimum does not exist.

Prove:

### 1

  n < n + 1

### 2

$\not\exists x^* \in S,\ \forall x \in S,\ f(x^*) \leq f(x)$

### 3

[Gödel’s Incompleteness Theorems](https://zh.wikipedia.org/wiki/%E5%93%A5%E5%BE%B7%E5%B0%94%E4%B8%8D%E5%AE%8C%E5%A4%87%E5%AE%9A%E7%90%86)

### 4

[Prisoner’s Dilemma](https://zh.wikipedia.org/wiki/%E5%9B%9A%E5%BE%92%E5%9B%B0%E5%A2%83)

### 5

θεός

## 📌 The Importance of Fixed Points

**Il apparaît que la répartition des revenus suit une loi… En Italie, 20% de la population possède 80% des terres**

prove:

### 1

  1(+/-)1=n

### 2

  n < n - 1

### 3

  [Pareto Principle](https://en.wikipedia.org/wiki/Pareto_principle)

### 4 Loss of a fixed point ⟹ The topological structure of the space is no longer complete.

Assume there exists a continuous mapping:

$f: X \to X$

If $f$ has no fixed point, that is:

$\neg \exists x \in X,\ f(x) = x$

Then the set $X$ does not possess the topological properties required by the Brouwer Fixed Point Theorem, namely:

$X \notin \text{CompactConvexSubsets}(\mathbb{R}^n)$

We can define:

**Topological Collapse**: a state in which $X$ loses compactness or convexity, resulting in the absence of fixed points.

Thus, we have:

$\neg \exists x \in X,\ f(x) = x \quad \Rightarrow \quad X \text{ undergoes topological collapse}$

