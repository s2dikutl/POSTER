# POSTER

# Evaluating Political Framing Effects on Large Language Models (LLMs)

This repository contains the dataset, automated judge evaluation rubrics, and R visualization code for the empirical study on how political framing influences LLM policy position scores across different public policy domains.

## Research Overview
- **Policy Domains:** Immigration, Climate Policy, Social Welfare[cite: 2]
- **Framing Conditions:** Neutral, Position A (Progressive/Open), Position B (Restrictive/Market)[cite: 2]
- **Iterations:** 5 repetitions per condition (Total = 45 responses)[cite: 2]
- **Evaluation Method:** LLM-as-a-Judge (1-5 Policy Position Scale)[cite: 2]

## Key Findings
1. **Framing Sensitivity:** Prompts with political framing successfully induced policy position shifts compared to neutral baselines[cite: 3, 4].
2. **Symmetric vs. Asymmetric Shifts:** Symmetric shifts (+1.00 / -1.00) were observed in Immigration and Climate Policy[cite: 3, 4]. In Social Welfare, the model exhibited resistance to restrictive framing (Position B yielded 3.00, resulting in +0.00 shift)[cite: 3, 4].
3. **High Reproducibility:** Low variance across 5 iterations confirmed high model response consistency[cite: 2, 5].

## Repository Contents
- `data/`: Contains raw LLM outputs and evaluated judge scores[cite: 2].
- `scripts/`: R scripts (`ggplot2`) used for data processing and figure generation.
- `figures/`: High-resolution figures generated for the research poster[cite: 1, 3, 4, 5, 6].

DILARA ELIF KUTLU
