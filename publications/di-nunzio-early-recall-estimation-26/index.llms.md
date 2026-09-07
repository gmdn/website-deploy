# Early Recall Estimation and Stopping in Technology-Assisted Reviews via Ranker-Sampler Fusion

Conference Paper

Published

May 28, 2026

**Di Nunzio, G. M.**

*Companion Proceedings of the ACM Web Conference 2026*, pp. 333–340

[PDF](paper.pdf) [DOI](https://doi.org/10.1145/3774905.3795598) [BibTeX](cite.bib)

## Abstract

Technology-Assisted Review (TAR) workflows iteratively prioritize documents for expert screening to achieve high recall (e.g., 0.90–0.95) under limited time and budget. A persistent challenge is deciding when to stop: true recall is unknown during live screening unless all documents are judged, while additional sampling to estimate recall can be prohibitively costly at low prevalence. This paper develops a step-by-step statistical framework to estimate recall early by fusing (i) information from a ranking model and (ii) a small probability sample of documents. We present two complementary estimators: a Bayesian prevalence estimator that treats the ranker as an informative prior updated by a random sample, and a model-assisted estimator (generalized regression estimator with a Horvitz-Thompson residual correction) that combines calibrated ranker probabilities with design-based sampling adjustments. We then derive practical stopping rules based on conservative (lower-bound) recall estimates, and outline a future evaluation plan on established constrained high-recall benchmarks.
