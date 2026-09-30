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
3. **Score Consistency: All five repetitions yielded identical policy-position scores within each issue × framing condition.

## Repository Contents
llm_judge_scores.csv: LLM-as-a-Judge policy-position scores and brief justifications.
RESPONSES-TABLE.Rmd: R code used for response tables and analysis.
PROMPTS.pdf: Experimental prompts and framing conditions.
RESPONSES.pdf: Model responses.
distribution.png, effect-of-political-framing.png, policy-score-matrix.png, policy-shift.png: Research figures.
1868317_appendix_poster.pdf: Poster appendix.

**ChatGPT Conversation Log:** (https://chatgpt.com/share/6abbad8b-c038-83eb-831f-8290e5618744)
