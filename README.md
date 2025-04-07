# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

My answers:

well the mappings of two graphs cant be one-to-one if there is a Vertice missing from one of the sets.
i believe that we need to prove that $V_1 <= V_2$ and $V_2 <= V_1$ for the mappings to be both 1-1 and Onto meaning:

let:
num_v_in_G1 = $G_1$.numVerticies()
num_v_in_G2 = $G_2$.numVerticies()

= num_v_in_G1 <= num_v_in_G2 & num_v_in_G1 >= num_v_in_G2

= num_v_in_G1 == num_v_in_G2

so we can understand that only when the number of verticies in both graphs are equal do we satisfy the one-to-one and onto part of the isomorphic graph definition.



I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.