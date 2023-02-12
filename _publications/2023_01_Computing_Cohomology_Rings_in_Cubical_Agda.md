---
title: Computing Cohomology Rings in Cubical Agda
date: 2023-01-11
datebis:
  year: 2023
  month: 01
  day: 11
spec: Distinguished Paper
authors:
  - name: Thomas Lamiaux
    link: /
  - name: Axel Ljungström
    link:
  - name: Anders Mörtberg
    link: https://staff.math.su.se/anders.mortberg/
venue:
  name: Certified Programs and Proofs 2023
  abrev: CPP 2023
  link: https://popl23.sigplan.org/home/CPP-2023#
arxiv: https://arxiv.org/abs/2212.04182
doi: https://dl.acm.org/doi/10.1145/3573105.3575677
file:
short-description:
  In the paper, we explain how to formalize Cohomology Rings in synthetic mathematics.
  With a special focus on data structures and how they influence formalization,
  most noticeably the direct sum and (multivariate) polynomials.
---

<!-- Abstract -->

In Homotopy Type Theory, cohomology theories are studied synthetically using higher inductive types and univalence. This paper extends previous developments by providing the first fully mechanized definition of cohomology rings. These rings may be defined as direct sums of cohomology groups together with a multiplication induced by the cup product, and can in many cases be characterized as quotients of multivariate polynomial rings. To this end, we introduce appropriate definitions of direct sums and graded rings, which we then use to define both cohomology rings and multivariate polynomial rings. Using this, we compute the cohomology rings of some classical spaces, such as the spheres and the Klein bottle. The formalization is constructive so that it can be used to do concrete computations, and it relies on the Cubical Agda system which natively supports higher inductive types and computational univalence.