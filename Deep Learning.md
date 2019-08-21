# Deep Learning

-------------------

[TOC]

## 线性代数

### 1.1 标量、向量、矩阵和张量
### 1.2 矩阵和向量相乘
### 1.3 单位矩阵、逆矩阵和正交阵
### 1.4 线性相关和生成子空间
### 1.5 范数
- 定义：设$\alpha$是内积空间V中的一个向量，则$\sqrt{\left<x,x\right>}$称为向量$\alpha$的模或者范数，记作$\lVert \alpha \lVert$.
- 定义：模为1的向量称为单位向量.
若$\alpha\ne 0$,则$\frac{\alpha}{\lVert \alpha \Vert}$为单位向量。
### 1.6 特殊类型的矩阵和向量
### 1.7 特征分解
### 1.8 奇异值分解
- 正定矩阵
定义：设A为n阶实对称矩阵，如果对于任意n元非零向量$x$,均有$x^TAx>0$,则称实对称矩阵A为正定矩阵（positive definite matrix）.称相应的$x^TAx$为正定二次型；如果$x^TAx\geqslant  0$,则称A为半正定矩阵（positive semi-definite matrix）.
性质：
（1）实对称矩阵正定的充分必要条件是它的所有特征值都为正，半正定则所有特征值为非负。
（2）正定矩阵的行列式为正，半正定矩阵的行列式为非负。
（3）正定矩阵的主对角线上的元素都大于0。
（4）正定矩阵可逆，且其逆矩阵也是正定矩阵。
- 性质： 
设$m \times n$矩阵A的秩$rank(A)=r$，则$A^TA$和$AA^T$分别是n阶和m阶对称矩阵，且$rank(A^TA)=rank(AA^T)=r$.设$\lambda$为$A^TA$的特征值，相应的特征向量为$v$,那么$\lambda$也是$AA^T$的特征值，相应的特征向量是$\frac{1}{\sqrt{\lambda}}Av$
- 奇异值
定义：设$m\times n$矩阵A的秩$rank(A)=r$,$A^TA$或者$AA^T$的非零特征值$\lambda_1,\lambda_2,...,\lambda_r$的算术平方根称为A的奇异值（singular value），记作$\sigma_1,...,sigma_r$,即$\sigma_i=\sqrt{\lambda_i} $($1\leqslant i \leqslant r$)
-奇异值分解（singular value decomposition）
定义：设$m\times n$矩阵A的秩$rank(A)=r$,则存在m阶正交矩阵$U$和n阶正交矩阵$V$使得$A=U\sum V^T$,其中$\sum $为$m\times n$分块对角阵
$$
	\sum = \left[ \begin{matrix}
	D& 0\\
	0& 0\\
	\end{matrix}\right]
$$
此处D是一个$r\times r$对角阵，D的对角线元素是A的奇异值$\sigma_1 \geqslant \sigma_2 \geqslant ... \geqslant \sigma_r > 0$v
### 1.9 Moore_Penrose伪逆

### 1.10 迹运算
### 1.11行列式

