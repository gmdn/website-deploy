# Screening Smarter, Not Harder: Budget Allocation Strategies for Technology-Assisted Reviews (TARs) in Empirical Medicine

Journal Article

Published

September 1, 2025

**Di Nunzio, G. M.**

*Machine Learning and Knowledge Extraction*, vol. 7, no. 3, pp. 104

[PDF](paper.pdf) [DOI](https://doi.org/10.3390/make7030104) [BibTeX](cite.bib)

## Abstract

In the technology-assisted review (TAR) area, most research has focused on ranking effectiveness and active learning strategies within individual topics, often assuming unconstrained review effort. However, real-world applications such as legal discovery or medical systematic reviews are frequently subject to global screening budgets. In this paper, we revisit the CLEF eHealth TAR shared tasks (2017–2019) through the lens of budget-aware evaluation. We first reproduce and verify the official participant results, organizing them into a unified dataset for comparative analysis. Then, we introduce and assess four intuitive budget allocation strategies—even, proportional, inverse proportional, and threshold-capped greedy—to explore how review effort can be efficiently distributed across topics. To evaluate systems under resource constraints, we propose two cost-aware metrics: relevant found per cost unit (RFCU) and utility gain at budget (UG@B). These complement traditional recall by explicitly modeling efficiency and trade-offs between true and false positives. Our results show that different allocation strategies optimize different metrics: even and inverse proportional allocation favor recall, while proportional and capped strategies better maximize RFCU. UG@B remains relatively stable across strategies, reflecting its balanced formulation. A correlation analysis reveals that RFCU and UG@B offer distinct perspectives from recall, with varying alignment across years. Together, these findings underscore the importance of aligning evaluation metrics and allocation strategies with screening goals. We release all data and code to support reproducibility and future research on cost-sensitive TAR.
