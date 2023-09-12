# feynman-colorflow: A LaTex package for drawing Feynman diagrams with color flows
![alt text](https://github.com/martinfoell/feynman-colorflow/blob/main/example.png)
# Install

```bash
git clone https://github.com/martinfoell/feynman-colorflow.git
```
# Basic usage
```latex
\documentclass{article}
\begin{document}

\usepackage{feynman-colorflow}

\begin{tikzpicture}
  \firstvertex{V1}{f,B,F}{-180,-90,0}
  \vertex{V2}{V1}{2}{f,F}{-180,0}
\end{tikzpicture}

\end{document}
```

## Particles
The particles that are included in the package are given in the table below.

| Particle    | Picture                                                                                   |
| -------- | ----------------------------------------------------------------------------------------- |
| Higgs  | ![alt text](https://github.com/martinfoell/feynman-colorflow/blob/main/images/higgs-1.png)|

