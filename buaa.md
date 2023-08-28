---
marp: true
theme: buaa_blue
paginate: true
math: katex
---

<!-- _class: lead -->

# Marp学术主题

#### BUAA academic theme


<br>

**作者**
Moreality 

YYYY/MM/DD

---

<!-- _class: chapter -->

# 一、基本功能
---

<style scoped> section header { font-size: 1em; } section p { font-size: 1em; } section li { font-size: .9em; } </style>

<!-- _header: 主题与特性 -->

本主题提供了一套**北航academic slide主题**， 主要基于[marp-theme-academic](https://github.com/kaisugi/marp-theme-academic)修改构建. 

- 主题基于[gaia](https://github.com/marp-team/marp-core/blob/main/themes/gaia.scss)
- 红色 / 蓝色支持 `./theme`
- BUAA logo
- 字体调整
- 代码块优化
- 一些简单的代码片段`./.vscode/marp.code-snippet`

---

<!-- _class: chapter -->

# 二、使用方法
---

<!-- _header: 基本的代码片段 -->

这是一段python代码, 支持auto-scaling

```python
def grid2list(grid):
    list_in = [[]]
    for grid_temp in grid:
        list_out = []
        for val in grid_temp:
            for list_temp in list_in:
                list_out.append(list_temp + [val]) # 注释
        list_in = list_out
    return list_in
def grid2list(grid):
    list_in = [[]]
    for grid_temp in grid:
        list_out = []
        for val in grid_temp:
            for list_temp in list_in:
                list_out.append(list_temp + [val])
        list_in = list_out
    return list_in
```
---

<!-- _header: 公式 -->

这是公式的展示, 由katex渲染支持: 

$$
\begin{align*}
y = y(x,t) &= A e^{i\theta} \\
&= A (\cos \theta + i \sin \theta) \\
&= A (\cos(kx - \omega t) + i \sin(kx - \omega t)) \\
&= A\cos(kx - \omega t) + i A\sin(kx - \omega t)  \\
&= A\cos \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big) + i A\sin \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big)  \\
&= A\cos \frac{2\pi}{\lambda} (x - v t) + i A\sin \frac{2\pi}{\lambda} (x - v t)
\end{align*}
$$

---

<!-- _header: 图片 -->

下图是一张居中的模糊图片, 更多marp的[图片语法请参考](https://marpit.marp.app/image-syntax)

![blur:2px width:800px center](https://i.imgur.com/rruErG9.jpg)

---

<!-- _header: 表格 -->

这是一个居中的表格: 

Fruit | Colour | Amount | Cost
-----|------|:-----:|------:
Banana | Yellow | 4 | £1.00
Apple | Red | 2 | £0.60
Orange | Orange | 10 | £2.50
Coconut | Brown | 1 | £1.50

--- 

<!-- _header: 注释 / 引用 -->

正文内容
正文内容
正文内容
正文内容
正文内容

> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
