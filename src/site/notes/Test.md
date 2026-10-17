---
{"dg-publish":true,"permalink":"/test/","dg-note-properties":{}}
---

这是我的第一篇测试笔记。

# 公式与图表测试

这是一篇用来验证渲染能力的笔记。测完可以删。

## 1. 行内公式

设直角三角形两直角边为 $a$、$b$，斜边为 $c$，则 $a^2 + b^2 = c^2$。

二次方程 $ax^2+bx+c=0$ 的判别式是 $\Delta = b^2-4ac$。

## 2. 单个块级公式

$$
\int_0^1 x^2 \, dx = \frac{1}{3}
$$

## 3. 多行对齐公式

$$
\begin{aligned}
E &= mc^2 \\
F &= ma \\
\Delta x \cdot \Delta p &\ge \frac{\hbar}{2}
\end{aligned}
$$

## 4. 矩阵与希腊字母

$$
A = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}, \quad
\theta = \sum_{i=1}^{n} \alpha_i
$$

## 5. 表格

| 函数 | 导数 | 定义域 |
|---|---|---|
| $\sin x$ | $\cos x$ | $\mathbb{R}$ |
| $\ln x$ | $1/x$ | $x>0$ |
| $e^x$ | $e^x$ | $\mathbb{R}$ |

## 6. 代码块

```python
def f(x):
    return x ** 2
```

代码块里的 `$x$` 不会被当成公式。

## 7. 高亮与任务

这段有 ==高亮文字==。

- [ ] 未完成的事
- [x] 已完成的事

## 8. Mermaid 图

```mermaid
flowchart LR
    A[写笔记] --> B[点发布]
    B --> C[Netlify 构建]
    C --> D[网页可见]
```

## 9. 脚注

这里有一个脚注引用[^demo]。

[^demo]: 这是脚注内容，会渲染在页面底部。
