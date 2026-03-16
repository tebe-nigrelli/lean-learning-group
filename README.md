# Installation and Project Setup

You may install Lean to code on VScode by following [the official guide]("https://lean-lang.org/install/").

1. *Create an empty project*: in VScode command `Lean 4: Project: Create Project Using Mathlib`. Depending on internet speed, this may take some time, but you can see a log of progress in real time.
2. *Open the folder*: use VScode `File: Open Folder`. Explore the files to get a sense of project structure, but only edit the ones in the `My_project_name/` folder, as the others are managed automatically.
3. *Import Mathlib*: you can import the mathematical library by writing `import Mathlib` as the first line in the `Basic.lean` file.
4. *Lean4 InfoView*: when opening `.lean` files, you can use `Lean 4: InfoView: Toggle InfoView` to understand the intermediate state of a proof. Placing the cursor in the middle of the proof will show the available information and the necessary steps next. If strange errors appear but the proof is correct, you can press the `Restart File` button

Formalization projects start with a blueprint, which gets filled progressively. A [sketch of the idea]("https://terrytao.wordpress.com/2023/11/18/formalizing-the-proof-of-pfr-in-lean4-using-blueprint-a-short-tour/") can be found on Terence Tao's blog, but a list of [exemplars and the installation guide]("https://github.com/PatrickMassot/leanblueprint/") are also available. For reference, an [overview of the available theorems]("https://leanprover-community.github.io/mathlib-overview.html").

---

# Related projects

## Project Template
**[Github Lean Project Template](https://github.com/pitmonticone/LeanProject)**
- [Other projects](https://github.com/pitmonticone/LeanProject) using the template.
  - [Infinity Cosmos](https://github.com/emilyriehl/infinity-cosmos) by Emily Riehl et al.
  - [Analytic Number Theory Exponent Database](https://github.com/teorth/expdb) by Terence Tao et al.
  - [Equational Theories](https://github.com/teorth/equational_theories) by Terence Tao et al.
  - [Groupoid Model of Homotopy Type Theory](https://github.com/sinhp/GroupoidModelofHoTTinLean4) by Sina Hazratpour et al.
  - [Soundness of FRI](https://github.com/BoltonBailey/FRISoundness) by Bolton Bailey et al.
  - [Weil's Converse Theorem](https://github.com/CBirkbeck/WeilConverse) by Chris Birkbeck et al.
  - [Proofs from THE BOOK](https://github.com/mo271/FormalBook) by Moritz Firsching et al.
  - [Automata Theory](https://github.com/shetzl/autth) by Stefan Hetzl et al.
  - [Dirichlet Nonvanishing](https://github.com/CBirkbeck/DirichletNonvanishing) by Chris Birkbeck et al.
  - [Seymour's Decomposition Theorem](https://github.com/Ivan-Sergeyev/seymour) by Ivan Sergeyev et al.
  - [Spectral Theorem](https://github.com/oliver-butterley/SpectralThm) by Oliver Butterley and Yoh Tanimoto.
  - [NeuralNetworks](https://github.com/or4nge19/NeuralNetworks) by Matteo Cipollina.
  - [ABC Exceptions](https://github.com/b-mehta/ABC-Exceptions) by Bhavik Mehta et al.
  - [Sphere Packing in 8 Dimensions](https://github.com/thefundamentaltheor3m/Sphere-Packing-Lean) by Maryna Viazovska et al.


## Comparison Projects

Sorted by Size and Relevance:
1. **Unit Fractions Density Conjecture**: [git](https://github.com/b-mehta/unit-fractions), [Paper](https://arxiv.org/pdf/2112.03726), [Blueprint](https://b-mehta.github.io/unit-fractions/blueprint/index.html)
2. **Liquid Tensor**: [git](https://github.com/leanprover-community/lean-liquid), [Paper](http://www.math.uni-bonn.de/people/scholze/Analytic.pdf) -> [image](project-papers/LEAN_ANALYTIC_9.4.png), [Blueprint](https://leanprover-community.github.io/liquid/).
3. **Arithmetic Progressions - Almost Periodicity**: [home](https://yaeldillies.github.io/LeanAPAP/), [Documentation](https://yaeldillies.github.io/LeanAPAP/docs/), [git](https://github.com/YaelDillies/LeanAPAP), [blueprint](https://yaeldillies.github.io/LeanAPAP/blueprint.pdf)
4. **Brauer Group and Galois Cohomology**: [paper](https://whysoserioushah.github.io/BrauerGroup_new/blueprint.pdf), [Code documentation](https://whysoserioushah.github.io/BrauerGroup_new/docs/), [blueprint](https://whysoserioushah.github.io/BrauerGroup_new/blueprint/)
5. **Brownian Motion**: [git](https://github.com/RemyDegenne/brownian-motion), [documentation](https://remydegenne.github.io/brownian-motion/docs/), [blueprint](https://remydegenne.github.io/brownian-motion/blueprint/), 
6. **Toric Varieties**: [Home](https://yaeldillies.github.io/Toric/index), [Paper without Lean references](https://yaeldillies.github.io/Toric/blueprint.pdf), [blueprint](https://yaeldillies.github.io/Toric/blueprint/), [upstream-ready](https://yaeldillies.github.io/Toric/upstreaming).
7. **Combinatorial Games**: [home](https://vihdzp.github.io/combinatorial-games/), [git](https://github.com/vihdzp/combinatorial-games), 
8. **Forbidden Matrix Theory**: [Overview](https://yaeldillies.github.io/ForbiddenMatrix/), [git](https://github.com/YaelDillies/ForbiddenMatrix), [blueprint code](https://github.com/YaelDillies/ForbiddenMatrix/tree/master/blueprint).
9. **∞-Cosmoi for Lean**: [home](https://emilyriehl.github.io/infinity-cosmos/), [blueprint](https://emilyriehl.github.io/infinity-cosmos/blueprint.pdf), [docs](https://emilyriehl.github.io/infinity-cosmos/docs/).

Related but through a different formalization language: [Busy Beaver Challenge](https://bbchallenge.org/7881560).

By Terence Tao:
- **Polynomial Freiman Ruzsa Conjecture**: [home](https://teorth.github.io/pfr/), [git](https://github.com/teorth/), [blueprint](https://teorth.github.io/pfr/blueprint/).
- **Magna Study**: [git](https://github.com/teorth/equational_theories).