# feynman-colorflow: A LaTex package for drawing Feynman diagrams with color flows
![alt text](https://github.com/martinfoell/feynman-colorflow/blob/main/example.png)
# Install

# Basic usage
```latex
\documentclass{article}
\begin{document}

\usepackage{feynman-colorflow}

\begin{tikzpicture}
  \firstvertex{V1}{f,B,F}{-180,-90,0}
  \vertex{V2}{V1}{2}{f,F}{-180,0}
  \SharedCoordinate{S11}{V1}{-180}{-90}{0.3}
  \draw[fill=red,draw=red] (S11) circle [radius=\r1];
  \SharedCoordinate{S11}{V2}{-180}{90}{0.3}
  \draw[fill=red,draw=red] (S11) circle [radius=\r1];
\end{tikzpicture}

\end{document}
```


