
![nature](https://github.com/user-attachments/assets/d6880334-8c17-4144-a1ad-fb983be3cefb)

<h1>Abstract</h1>

We propose PhiTransformer, a geometry-aware Transformer guided by phyllotaxis (golden
angle) and fractal self-similarity. Tokens occupy a golden-angle spiral; attention combines
annulus-banded locality with φ-scaled hierarchical “spine” links; embeddings may be tied
across φ-scales. The resulting O(n log n) connectivity aims to reduce attention compute
while preserving long-range information flow. We formalize the topology, provide CPU and
Triton reference kernels, estimate training/inference gains, and outline an experimental
plan for validation. Claims of efficiency are explicitly speculative pending experiments.

<img width="1518" height="1597" alt="phi_transformer_diagram" src="https://github.com/user-attachments/assets/9738dbaa-6f40-4869-80f4-3eac8d21e2eb" />
