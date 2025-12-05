# Symmetric edge polytopes
Given a simple graph $G=(V,E)$, its \emph{symmetric edge polytope} is defined as the convex hull of vectors of the form $\pm (e_v - e_w)$ whenever there is an edge between $v$ and $w$.
The vectors $e_v$ and $e_w$ are unit vectors of the space $\mathbb{R}^{|V|}$.

# Database of biconnected graphs on 3 up to 10 vertices.
All the csv files are semicolon separated (commas are to be ignonored!) and have four columns:
- degree sequence
- characteristic polynomial
- a graph code (can be decoded with the function decode_graph in the attached jupyter notebook
- first 100 terms of the Ehrhart series of the symmetric edge polytope of the graph associated
