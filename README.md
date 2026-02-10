
# User-Centered Analysis of AI-Related Psychological Risk

This repository contains the code used in the paper  
"Understanding Risk and Dependency in AI Chatbot Use from User Discourse“.

It supports a large-scale, user-centered analysis of AI-related psychological risk using Reddit discourse, combining LLM-assisted thematic analysis, emotion labeling, and visualization.

---

## Data

This repository does not redistribute raw Reddit posts. All data used in the analysis were collected from publicly available Reddit communities and processed locally. To protect user privacy, only anonymized examples and summarized representations of posts are included.

---

## Scripts

The `scripts/` directory contains the core analysis pipeline:

- `thematic_analysis/`  
  LLM-assisted thematic analysis following Braun and Clarke’s reflexive framework, including multi-agent role simulation and post-level theme assignment.

- `emotion_labeling/`  
  BERT-based emotion classification assigning probabilistic scores for anger, fear, sadness, joy, disgust, and surprise.

- `visualization/`  
  Scripts for generating phrase-based word clouds and radar charts of averaged non-neutral emotional profiles across experiential dimensions.

- `summary_posts/`  
  Utilities for generating privacy-preserving summaries of representative user posts used for interpretive illustration in the paper and Appendix.

---

## Reproducibility

The provided scripts allow reproduction of the main analyses and figures reported in the paper, excluding raw data. All models and libraries used are publicly available.

---

## Ethical Note

This repository is designed with privacy protection as a core principle. Raw user-generated content is not shared, and all example materials are anonymized or summarized in accordance with the procedures described in the paper.

---

## Citation

If you use this code, please cite the associated paper.
