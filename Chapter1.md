# 2D射影几何

## 点与直线

点的齐次表示

$$
\mathbf{x} = (x,y,1)^T
$$

直线的表示

$$
\mathbf{l} = (a,b,c)^T
$$

点$\mathbf{x}$在直线$\mathbf{l}$的充要条件为$\mathbf{x}^T\mathbf{l} = 0$

直线有2个自由度

两直线交点$\mathbf{x} = \mathbf{l} \times \mathbf{l'}$

通过两点的直线$\mathbf{l} = \mathbf{x} \times \mathbf{x'}$

## 理想点和无穷远线

平行线 $\mathbf{l} = (a,b,c)^T, \mathbf{l'} = (a,b,c')^T$ 的交点 $\mathbf{x} = (b, -a, 0)^T$

$x_3 = 0$ 的点称为**理想点**，或者**无穷远点**

所有理想点$(x_1,x_2,0)^T$，由$x_1/x_2$指定一个具体的点。理想点集合在一条直线$\mathbf{l}_\infty$上，称为**无穷远线**

$\mathbf{l} = (a,b,c)^T$与$\mathbf{l}_\infty$交于理想点$(b,a,0)^T$,任何一条与$\mathbf{l}$平行的线$\mathbf{l'} = (a,b,c')^T$也与$\mathbf{l}_\infty$交于该点。所以交点与$c'$取值无关。非齐次表示下，$(b,-a)^T$代表直线的**方向**。

引入无穷远点后，在射影平面$IP^2$中，任何相异直线都相交于一点，与标准欧式几何$IR^2$不同。
