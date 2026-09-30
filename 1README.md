# KUTLU_POSTER
**Author:** Dilara Elif KUTLU 
**Registration Number:** 1868317
**Affiliation:** University of Trier – English Linguistics  
**Course / Project:** NLP
**Date:** 30th September 2026

# Evaluating Political Framing Effects on Large Language Models (LLMs)

This repository contains the dataset, automated judge evaluation rubrics, and R visualization code for the empirical study on how political framing influences LLM policy position scores across different public policy domains.

## Research Overview
- **Policy Domains:** Immigration, Climate Policy, Social Welfare
- **Framing Conditions:** Neutral, Position A (Progressive/Open), Position B (Restrictive/Market)
- **Iterations:** 5 repetitions per condition (Total = 45 responses)
- **Evaluation Method:** LLM-as-a-Judge (1-5 Policy Position Scale)

## Key Findings
1. **Framing Sensitivity:** Prompts with political framing successfully induced policy position shifts compared to neutral baselines.
2. **Symmetric vs. Asymmetric Shifts:** Symmetric shifts (+1.00 / -1.00) were observed in Immigration and Climate Policy. In Social Welfare, the model resisted restrictive framing (Position B yielded 3.00, resulting in a +0.00 shift).
3. **High Reproducibility:** Low variance across 5 iterations confirmed high model response consistency.

## Repository Contents
- `data/`: Contains raw LLM outputs and evaluated judge scores.
- `scripts/`: R scripts (`ggplot2`) used for data processing and figure generation.
- `figures/`: High-resolution figures generated for the research poster.

**ChatGPT Conversation Log:** (https://chatgpt.com/share/6abbad8b-c038-83eb-831f-8290e5618744)
