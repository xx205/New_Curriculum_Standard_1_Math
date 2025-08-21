一、选择题：本大题共 8 小题，每小题 5 分，共计 40 分。每小题给出的四个选项中，只有一个选项是正确的。请把正确的选项填涂在答题卡相应的位置上。

1.  $(1+5i)i$ 的虚部为
    A. $-1$
    B. $0$
    C. $1$
    D. $6$

2.  设全集 $U=\{1,2,3,4,5,6,7,8\}$，集合 $A=\{1,3,5\}$，则 $ \complement_U A $ 中元素个数为
    A. $0$
    B. $3$
    C. $5$
    D. $8$

3.  若双曲线 $C$ 的虚轴长为实轴长的 $\sqrt{7}$ 倍，则 $C$ 的离心率为
    A. $\sqrt{2}$
    B. $2$
    C. $\sqrt{7}$
    D. $2\sqrt{2}$

4.  若点 $(a,0) (a>0)$ 是函数 $y=2\tan(x-\frac{\pi}{3})$ 的图象的一个对称中心，则 $a$ 的最小值为
    A. $\frac{\pi}{6}$
    B. $\frac{\pi}{3}$
    C. $\frac{\pi}{2}$
    D. $\frac{4\pi}{3}$

5.  设 $f(x)$ 是定义在 $\mathbb{R}$ 上且周期为 $2$ 的偶函数，当 $2 \le x \le 3$ 时，$f(x)=5-2x$，则 $f(-\frac{3}{4})=$
    A. $-\frac{1}{2}$
    B. $-\frac{1}{4}$
    C. $\frac{1}{4}$
    D. $\frac{1}{2}$

6.  帆船比赛中，运动员可借助风力计测定风速的大小和方向，测出的结果在航海学中称为视风风速，视风风速对应的向量，是真风风速对应的向量与船行风速对应的向量之和，其中船行风速对应的向量与船速对应的向量大小相等，方向相反。图 1 给出了部分风力等级、名称与风速大小的对应关系。已知某帆船运动员在某时刻测得的视风风速对应的向量与船速对应的向量如图 2（风速的大小和向量的大小相同，单位 m/s），则真风为
    A. 轻风
    B. 微风
    C. 和风
    D. 劲风

```latex
\documentclass[tikz, border=3mm]{standalone}
\usepackage[UTF8]{ctex}

\begin{document}
\begin{tikzpicture}[
    axis/.style={->, >=latex, thick},
    grid/.style={dashed, gray!60},
    vector/.style={->, >=latex, very thick, black}
]

\draw[grid] (0,0) grid (3,3);

\draw[axis] (0,0) -- (3.5,0) node[right] {$x$};
\draw[axis] (0,0) -- (0,3.5) node[above] {$y$};

\node[below left] at (0,0) {O};

\foreach \x in {1,2,3} {
    \draw (\x, 2pt) -- (\x, -2pt) node[below] {$\x$};
}

\foreach \y in {1,2,3} {
    \draw (2pt, \y) -- (-2pt, \y) node[left] {$\y$};
}

\draw[vector] (2,0) -- (3,3);

\draw[vector] (3,3) -- (0,2);

\node at (2.5, 0.7) {船速};

\node at (1.5, 2.7) {视风风速};

\end{tikzpicture}
\end{document}
```

| 等级 | 风速大小 | 名称 |
| :--- | :--- | :--- |
| 2 | 1.1~3.3 | 轻风 |
| 3 | 3.4~5.4 | 微风 |
| 4 | 5.5~7.9 | 和风 |
| 5 | 8.0~10.1 | 劲风 |


7. 若圆 $x^2 + (y+2)^2 = r^2 (r>0)$ 上到直线 $y = \sqrt{3}x + 2$ 的距离为 $1$ 的点有且仅有 2 个, 则 r 的取值范围是
   A. (0,1)
   B. (1,3)
   C. (3,+∞)
   D. (0,+∞)

8. 若实数 $x, y, z$ 满足 $2+\log_2 x = 3+\log_3 y = 5+\log_5 z$, 则 $x, y, z$ 的大小关系不可能是
   A. $x>y>z$
   B. $x>z>y$
   C. $y>x>z$
   D. $y>z>x$