# Contributing to awesome-gnn-theory

Thank you for helping keep this reading map useful. The goal is not to collect every paper that uses a graph neural network, but to curate work that helps readers understand the theory, limits, design principles, and scientific use of GNNs.

## What Belongs Here

Good additions usually satisfy at least one of these criteria:

- The paper introduces or clarifies a theoretical concept for GNNs, such as expressivity, WL hierarchy, logic, spectral theory, equivariance, oversquashing, graph limits, optimization, or generalization.
- The paper changes how we understand a major GNN architecture family, such as MPNNs, subgraph GNNs, graph transformers, temporal GNNs, or equivariant atomistic models.
- The paper is a high-quality survey, benchmark, or framework that helps researchers navigate the field.
- The paper connects GNN theory to scientific machine learning, such as PDE solvers, molecular modeling, interatomic potentials, particle physics, geoscience, or cosmology.

## What Usually Does Not Belong

Please avoid adding papers that are purely application-driven unless they expose a theory-relevant insight, benchmark, or architecture. For example, a traffic forecasting paper with no new graph modeling principle is better suited for a separate applications list.

Please also avoid:

- duplicate entries,
- unstable links from temporary mirrors,
- papers without a clear venue/year or arXiv/OpenReview/proceedings page,
- long annotations for every entry.

## Preferred Entry Format

Use a stable link whenever possible:

```md
1. Author, A., et al. [Paper Title.](https://stable-link.example) Venue or arXiv preprint (Year).
```

For landmark or frontier papers, a short curator note is welcome:

```md
> Note: Explains why this result changes how we understand GNN expressivity or transfer.
```

## Suggested Pull Request Checklist

- The paper is placed in the most relevant section.
- The link is stable and not a temporary `casa_token` URL.
- The entry includes title, authors, venue or arXiv, and year.
- If the paper is very application-heavy, the PR explains why it belongs in a theory-focused map.
- The PR does not introduce duplicate entries.

## Curation Philosophy

This repository should remain opinionated. It is better to have a smaller list with clear structure and research insight than a very large list where readers cannot decide what matters.
