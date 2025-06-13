---
title: structure note
date: 2023-04-28
aliases:
tags:
  - concept
  - review
status: growing
public: true
---
Part of [[Zettelkasten and Evergreen MOC]]

> [!NOTE] What is a Structure Note?
> A **structure note** (also called a "hub note" or "index note") is a **meta-note** that organizes and connects related atomic notes within your zettelkasten. Rather than containing original content, it serves as a **roadmap** or **thumbnail** that shows relationships between ideas and provides **entry points** into clusters of knowledge.

In my head I call them *structure* notes, but in writing “MOCs”, as it is shorter and an easy [[Note titles are like a thumbnail|thumbnail]].

## Purpose and Function

Structure notes solve the **discoverability problem** in large zettelkasten systems by:

- **Creating pathways** through your knowledge network
- **Grouping related concepts** without rigid hierarchy
- **Providing context** for how ideas connect
- **Serving as launching points** for exploration
- **Maintaining emergent organization** rather than predetermined categories

### Example: Advanced Structure Note with Descriptions
```markdown
# Machine Learning - Structure Note

## Foundational Mathematics
- [[Linear Algebra for ML]] - vectors, matrices, eigenvalues
- [[Statistics and Probability]] - distributions, hypothesis testing  
- [[Calculus in ML]] - derivatives for optimization

## Core Algorithms

### Supervised Learning
- [[Linear Regression]] - predicting continuous values
  - Connected to: [[Gradient Descent]], [[Feature Engineering]]
- [[Decision Trees]] - interpretable classification
  - Extends to: [[Random Forest]], [[Gradient Boosting]]
- [[Neural Networks]] - universal function approximators
  - Deep dive: [[Backpropagation Algorithm]]

### Unsupervised Learning  
- [[K-Means Clustering]] - grouping similar data points
- [[Principal Component Analysis]] - dimensionality reduction
- [[Association Rules]] - finding item relationships

## Implementation and Tools
- [[Python for ML]] ↔ [[Scikit-learn Library]]
- [[Data Preprocessing Pipeline]]
- [[Model Evaluation Metrics]]

## Real-World Applications
See [[ML Case Studies Structure]] for detailed examples

## Questions to Explore
- How does [[Bias-Variance Tradeoff]] affect model selection?
- When should you choose [[Ensemble Methods]] over single models?

---
**Meta**: This structure note connects to [[Statistics Structure]], [[Programming Structure]]
**Status**: Actively developing | **Review Date**: 2024-02-01
```

## Key Characteristics

### What Makes a Good Structure Note

1. **Flexible Organization**: Groups notes by natural relationships, not rigid categories
2. **Multiple Entry Points**: Provides various ways to enter the topic depending on your current interest
3. **Bidirectional Links**: Uses `[[Internal Links]]` to connect to atomic notes, which should link back
4. **Emergent Hierarchy**: Organization emerges from actual connections rather than predetermined structure
5. **Living Document**: Evolves as your understanding and note collection grows

### Structure Note vs. Regular Note

|Structure Note|Atomic Note|
|---|---|
|**Organizes** other notes|**Contains** original ideas|
|**Maps relationships**|**Develops single concept**|
|**Provides overview**|**Goes deep on topic**|
|**Changes frequently**|**Relatively stable**|
|**Links outward** heavily|**Links both ways**|

## Advanced Patterns

### Nested Structure Notes

```markdown
# Web Development - Master Structure

## Frontend Development  
See [[Frontend Development Structure]] for detailed breakdown

## Backend Development
See [[Backend Development Structure]] for server-side topics  

## DevOps and Deployment
See [[DevOps Structure]] for infrastructure topics

## Cross-Cutting Concerns
- [[Security Best Practices]]
- [[Performance Optimization]]  
- [[Testing Strategies]]
```

### Timeline-Based Structure

```markdown
# Personal Learning Journey - 2024

## Q1 Focus: Machine Learning Fundamentals
- [[January ML Study Plan]]
- [[February Deep Learning Exploration]] 
- [[March NLP Projects]]

## Q2 Focus: System Design
- [[April Scalability Patterns]]
- [[May Database Deep Dive]]
- [[June Microservices Architecture]]

## Key Insights This Year
- [[The Importance of Mathematical Foundations]]
- [[Why Practice Projects Matter More Than Theory]]
```

This would probably be a [[project]] (when activated)

## Obsidian-Specific Features

### Using Tags for Structure Notes

```markdown
#structure-note #programming #active

# Data Structures and Algorithms

%% These tag combination helps filter structure notes %%
```

### Graph View Navigation

Structure notes become **hubs** in Obsidian's graph view, showing as highly connected nodes that help navigate your knowledge network visually.

The graph view, although until now (for me) not al that useful, it helps to get an overview, they make it easier to notice what’s missing.

## Best Practices

### Creating Structure Notes

1. **Start Small**: Begin with 3-5 related notes, expand organically
2. **Use Consistent Naming**: Consider suffixes like "- Structure" or "- MOC" (MOC is shorter 😆)
3. **Regular Maintenance**: Review and update as your note collection grows
4. **Cross-Link Structures**: Connect related structure notes to each other
5. **Balance Depth**: Don't make structure notes too deep - create nested ones instead (still needs to be [[atomic note|atomic]], about one thing)

### Maintenance Workflow

1. **Weekly Review**: Check if new notes need to be added to existing structures
2. **Monthly Restructuring**: Reorganize based on how your understanding has evolved
3. **Quarterly Cleanup**: Remove dead links, consolidate similar structures

> [!NOTE] Important
> Structure notes are the **nervous system** of your zettelkasten - they don't contain the knowledge itself, but they make it possible to navigate and discover connections within your growing collection of ideas. Outdated structure notes turn parts of your ZK inaccessible.

## (Primary) Sources
Example of a structure note: [§Note-writing systems](https://notes.andymatuschak.org/%C2%A7Note-writing_systems)

Ahrens:
![[ahrens_2022#^hsover01]]
