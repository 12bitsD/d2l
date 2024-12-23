# 信息论基础

---

## 熵

- 熵 量化数据中的信息内容。

$$
H[P] = \sum_{j} - P(j) \log P(j) 
$$

- 编码从分布 \( P \) 中抽取的数据至少需要 \( H[P] \) 纳特（nat）。
- 1 纳特 ≈ 1.44 比特。

## 信息量

- 可预测的数据容易压缩。
- 信息量 −log*P*(*j* ) 量化事件 j 的惊异程度。
- 低概率事件信息量更大。

## 交叉熵

- 交叉熵 H(P, Q)  是主观概率  Q  的观察者在看到 P  生成数据时的预期惊异。
- 当 P = Q时，交叉熵最小，H(P, P) = H(P) 。
- 交叉熵分类目标：
    1. 最大化似然；
    2. 最小化惊异。