17. (15分) 如图所示的四棱锥 $P-ABCD$ 中，$PA \perp$ 平面 $ABCD$，$BC // AD$，$AB \perp AD$.

```latex
\documentclass[tikz, border=5pt]{standalone}
\usepackage{tikz}

\begin{document}
\begin{tikzpicture}[
    scale=1.2,
    x={(-0.8cm, -0.4cm)}, 
    y={(1cm, -0.3cm)},
    z={(0cm, 1cm)},
    line cap=round,
    line join=round
]

\coordinate (A) at (0, 0, 0);
\coordinate (P) at (0, 0, 2.5);
\coordinate (B) at (2, 0, 0);
\coordinate (D) at (0, 3, 0);
\coordinate (C) at (2, 1.8, 0);

\draw[dotted, thick] (P) -- (A);
\draw[dotted, thick] (A) -- (D);

\draw[thick] (A) -- (B);
\draw[thick] (B) -- (C);
\draw[thick] (C) -- (D);
\draw[thick] (D) -- (P);
\draw[thick] (P) -- (B);
\draw[thick] (P) -- (C);

\node[below left] at (A) {A};
\node[left] at (B) {B};
\node[right] at (C) {C};
\node[right] at (D) {D};
\node[above] at (P) {P};

\end{tikzpicture}
\end{document}
```

(1) 证明：平面 $PAB \perp$ 平面 $PAD$;

(2) 若 $PA = AB = \sqrt{2}$，$AD = \sqrt{3}+1$，$BC = 2$，$P, B, C, D$ 在同一个球面上，设该球面的球心为 $O$.
    (i) 证明：$O$ 在平面 $ABCD$ 上;
    (ii) 求直线 $AC$ 与直线 $PO$ 所成角的余弦值。