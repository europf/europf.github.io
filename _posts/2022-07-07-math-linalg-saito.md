---
layout: post
title:  "斎藤毅『線形代数の世界』読書メモ"
tags: 数学
excerpt_separator: <!--more--> 
---

斎藤毅『線形代数の世界』読書メモです. <!--more-->

## 第1章 線型空間

### 1.3

- 例 1.3.6
    - $\mathbb{R}$ の元による乗法でスカラー倍を定義している.

### 1.4
- 系 1.4.10
    - なんかここだけ行間が広い気がするので後で書く.
- p. 23「$x_1, \ldots, x_n \in V$ が $V$ の基底である $\iff$ $V=Kx_1 \oplus \cdots \oplus Kx_n$ かつ $x_1, \ldots, x_n$ がどれも $0$ でない」について
    - $(\implies):$ 前者の条件より $(b_1 x_1, \ldots, b_n x_n) \mapsto b_1 x_1 + \cdots + b_n x_n$ 可逆. 後者の条件より $(b_1, \ldots, b_n) \mapsto (b_1 x_1, \ldots, b_n x_n)$ 可逆. よって2つの合成も可逆. (cf. prop. 1.2.3)
    - 仮定より $(b_1, \ldots, b_n) \mapsto b_1 x_1 + \cdots + b_n x_n$ 可逆. $x_i = 0$ なる $i$ があると上の可逆性に矛盾. よって $x_1, \ldots, x_n \neq 0$ で, $(b_1, \ldots, b_n) \mapsto (b_1 x_1, \ldots, b_n x_n)$ 可逆. よって合成も可逆つまり $V=Kx_1 + \cdots + Kx_n=Kx_1 \oplus \cdots \oplus Kx_n$.

### 1.6
- 定理 1.6.4 最後
    - 系1.5.7 を $V = \langle y_j \mid j \in A \rangle$ として使う.

## 第3章 自己準同形

### 3.2
- 命題 3.2.7:

### 3.7 
- 命題 3.7.2 証明, 1. で帰納法を使うところ
    - $\|a_{n+1}\|=\|p_1 a_n + \cdots + p_m a_{n-m+1}\| \leq \|P\|(\|a_n\| + \cdots + \|a_{n-m+1}\|) \leq m\|P\|(m\|P\|)^{n-m+1}\|A\| = (m\|P\|)^{(n+1)-m+1}\|A\|$.
- 命題 3.7.5 証明
    - $P_a$ は同形 $W_0(m) \to W_a(m)$ を定める. は $V_0(m) \to V_a(m)$ が正しい. 次の行の $W_a(m)$ も $V_a(m)$ が正しい.

### 参考文献:
[1] 斎藤毅『線形代数の世界』東京大学出版会 第5刷