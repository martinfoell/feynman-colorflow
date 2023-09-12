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

| Particle | Variable | Picture                                                                                   |
| -------- | -------- | ----------------------------------------------------------------------------------------- |
| Fermion (incomming) | f        | ![alt text](https://github.com/martinfoell/feynman-colorflow/blob/main/images/fermion1.png)|
| Fermion (outgoing) | F        | ![alt text](https://github.com/martinfoell/feynman-colorflow/blob/main/images/fermion2.png)|
| Boson (plus) | b        | ![alt text](https://github.com/martinfoell/feynman-colorflow/blob/main/images/boson1.png)|
| Boson (minus) | B        | ![alt text](https://github.com/martinfoell/feynman-colorflow/blob/main/images/boson2.png)|
| Gluon (plus) | g        | ![alt text](https://github.com/martinfoell/feynman-colorflow/blob/main/images/gluon1.png)|
| Gluon (minus) | G        | ![alt text](https://github.com/martinfoell/feynman-colorflow/blob/main/images/gluon2.png)|
| Higgs | H        | ![alt text](https://github.com/martinfoell/feynman-colorflow/blob/main/images/higgs1.png)|




