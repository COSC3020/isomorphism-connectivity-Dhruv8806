[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12699294&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

To prove that isomorphic graphs do not have to be completely connected. As considering two graphs, $A$ and $B$. Graph $A$ consists of nodes $\ A, B,$ and $C$ , connected by edges $\ (A, B)$ and $\ (B, C)$ and Graph $B$ consists of nodes $\ X, Y,$ and $Z$ with edges $\ (X, Y)$ and $\ (Y, Z)$ . The bijection function $\ f : V1 \rightarrow V2$, where $\ f(A) = X, f(B) = Y,$ and $\ f(C) = Z$, as it satisfies the one-to-one and onto (bijection) function requirement for isomorphism. Furthermore, for every edge $\ (u, v) ∈ E1$, there is a corresponding edge $\ (f(u), f(v)) ∈ E2 $. For example, the edge $\ (A, B) ∈ E1$ aligns with $\ (X, Y) ∈ E2$, demonstrating isomorphism. However, both Graph $A$ and Graph $B$ are not completely connected, with only two edges each, leaving some nodes not connected.

Sources Used: TA
