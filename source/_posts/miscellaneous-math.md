---
title: 向量与线性代数
category: 计算机图形学基础
mathjax: true
---


<div style="overflow-x:hidden">

### 向量 
- $$ 向量通常写做\space \vec{a} 或者 \boldsymbol{a} \hspace{30cm} $$
- $$ 向量也可以使用起点和终点表示\space \vec{AB} = \boldsymbol{B} - \boldsymbol{A} \hspace{30cm} $$
- $$ 向量具有方向和长度 \hspace{30cm}$$
- $$ 向量的长度写做\space \mid\mid\vec{a}\mid\mid \hspace{30cm} $$

### 单位向量
- $$ 模长为1的向量就是单位向量 \hspace{30cm} $$
- $$ 计算公式为\space \hat{a} = \frac {\vec{a} } {\mid\mid\vec{a}\mid\mid} \hspace{30cm} $$

### 向量求和
![  ](https://img-blog.csdnimg.cn/img_convert/4dcd173bc2fdc1170e0ae119797f353f.png)

- $$ 根据平行四边行法则和三角形法则可得\space \vec{c} = \vec{a} + \vec{b} \hspace{30cm}$$
- $$ 向量默认是列向量 \hspace{30cm}$$
- $$ 向量的转置即行和列互换 \space \boldsymbol{A} = \begin{pmatrix} x \\ y \end{pmatrix} \space \space \boldsymbol{A}^T = \begin{pmatrix} x & y \end{pmatrix} \hspace{30cm} $$

### 向量点乘
- $$\text{两个向量点乘会得到一个数，也可以计算两个向量的夹角} \hspace{30cm}$$
$$\vec{a} \cdot \vec{b}= {\mid\mid\vec{a}\mid\mid}{\mid\mid\vec{b}\mid\mid} \cos\theta \hspace{30cm}$$
$$\cos\theta = \frac{\vec{a} \cdot \vec{b} } {\mid\mid\vec{a}\mid\mid \mid\mid\vec{b}\mid\mid} \hspace{30cm}$$
- $$\text{点乘的性质：} \hspace{30cm}$$
$$\vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{a} \hspace{30cm}$$
$$\vec{a} \cdot \left( \vec{b} + \vec{c} \right) = \vec{a} \cdot \vec{b} + \vec{a} \cdot \vec{c} \hspace{30cm}$$
$$ \left(k\vec{a} \right) \cdot \vec{b} = \vec{a} \cdot \left(k\vec{b} \right) = k\left(\vec{a} \cdot \vec{b} \right) \hspace{30cm}$$

- $$\text{在笛卡尔坐标系中：} \hspace{30cm}$$
$$2d: \vec{a} \cdot \vec{b} = \begin{pmatrix} x \\ y \end{pmatrix} \cdot \begin{pmatrix} x \\ y \end{pmatrix} = x_a + x_b + y_a + y_b  \hspace{30cm}$$
$$3d: \vec{a} \cdot \vec{b} = \begin{pmatrix} x \\ y \\ z \end{pmatrix} \cdot \begin{pmatrix} x \\ y \\ z \end{pmatrix} = x_a + x_b + y_a + y_b + z_a + z_b  \hspace{30cm}$$

- $$\text{点乘的作用：} \hspace{30cm}$$
[1.找到两个向量之间的余弦夹角](#向量点乘)
$$\text{2.一个向量投影到另一个向量上的长度} \hspace{30cm}$$ 
![](https://img-blog.csdnimg.cn/img_convert/1c322f4d029573752e7f90f9c2565d5a.png)
![](https://img-blog.csdnimg.cn/img_convert/258841074cadcda274127d12c7f6aff9.png)
$$\vec{b}_\bot = k\vec{a} \hspace{30cm}$$
$$k = \mid\mid\vec{b}_\bot\mid\mid = \mid\mid\vec{b}\mid\mid\cos\theta \hspace{30cm}$$

$$\text{3.判断两个向量的前后或者距离} \hspace{30cm}$$ 
![](https://img-blog.csdnimg.cn/img_convert/29003635d4185a652c45c133ae395e41.png)

$$\text{方向性：点乘为正方向比较一致反之方向差不多相反} \hspace{30cm}$$ 
$$\text{距离性：1为重合，由1到0，再由0到-1，可以用于镜面反射，从出射光方向看过去会非常亮，入射光则不然，金属高光同理} \hspace{30cm}$$ 



### 向量叉乘


</div>



