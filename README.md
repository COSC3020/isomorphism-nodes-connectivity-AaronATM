[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ppBU16qM)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Proof:

Let $G_{1}$, $G_{2}$ be any fully connected graphs with $u_{n}$, $v_{n}$ and $u_{t}$, $v_{t}$ being any vertices in $G_{1}$, $G_{2}$ respectively.

Due to the full connectivity of the graph, for any edge $E_{n}$ in $G_{1}$, we can find a one-to-one and onto function $f: u_{n} \rightarrow v_{n}$ such that $(u_{n}, v_{n}) \in E_{n}$.

Subsequently, for any edge $E_{t}$ in $G_{2}$ we can find a function such that $(f(u_{n}), f(v_{n})) = (u_{t}, v_{t}) \in E_{t}$.

Thus, any two fully connected graphs are also isomorphic.
