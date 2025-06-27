## n 的维度里面没有全局最优解

**不识庐山真面目，只缘身在此山中**

全局最优解和局部最优解是相对的。

局部最优解只能无限逼近全局最优解。

由于 n+1 维的干涉，再加上建模的时候，无法考虑所有维度，导致全局最优解并不存在。

证明:

### 1

  n < n + 1

### 2

$\not\exists x^* \in S,\ \forall x \in S,\ f(x^*) \leq f(x)$

❌ 集合 S 中不存在最小值点（极小值）/ 最优解、全局最优解不存在

### 3

[哥德爾不完備定理](https://zh.wikipedia.org/wiki/%E5%93%A5%E5%BE%B7%E5%B0%94%E4%B8%8D%E5%AE%8C%E5%A4%87%E5%AE%9A%E7%90%86)

### 4

[囚徒困境](https://zh.wikipedia.org/wiki/%E5%9B%9A%E5%BE%92%E5%9B%B0%E5%A2%83)

### 5

人外有天，天外有神

## n维空间存在不动点

**知所先后，则近道矣**

证明:

### 1: 1(+/-)1=n

### 2: n < n - 1

### 3: 80/20 法则

### 4 n维空间不动点的重要性

假设存在连续映射：

$f: X \to X$

如果 $f$ 没有不动点，即：

$\neg \exists x \in X,\ f(x) = x$

则说明集合 $X$ 不具备 Brouwer 不动点定理成立所需的拓扑性质，即：

$X \notin \text{CompactConvexSubsets}(\mathbb{R}^n)$

进一步，可以定义：

**拓扑坍塌（Topological Collapse）**：当 $X$ 失去紧性或凸性，导致不动点不存在的状态。

因此我们有：

$\neg \exists x \in X,\ f(x) = x \quad \Rightarrow \quad X \text{ 拓扑结构坍塌}$