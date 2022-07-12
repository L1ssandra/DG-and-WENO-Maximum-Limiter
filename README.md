对于一维和二维的双曲守恒律 u_t + \nabla·f(u) = 0，极值原理表明：如果初值满足u0(x)∈[m,M]，\forall x，则在任意时刻有u(x,t)∈[m,M],\forall x,t。
这个程序复现了文献中的保极值限制器，用DG做了二维的一些例子，WENO做了一维的一些例子。

Reference: Xiangxiong Zhang and Chi-Wang Shu, On maximum-principle-satisfying high order schemes for scalar conservation laws.
