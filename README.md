# Operationalizing Koller's Equivalence Framework in Large Language Models

Code and data for the paper: "Operationalizing Koller's Equivalence Framework in Large Language Models: Parameter Optimization for Equivalence-Specific Machine Translation"

Author: H. Shariati, PhD Candidate in Translation Studies, University of Isfahan

## Overview
This repository contains the data and analysis for a study on whether decoding-time parameter control in TranslateGemma 4B produces equivalence-specific improvements in Kurdish → English translation.

## Contents
- data/sentences.md — The 5 Kurdish source sentences and Awta reference translations
- data/translations.md — Default and modified outputs from TranslateGemma 4B
- data/parameters.csv — Parameter settings per equivalence type
- data/mqm_scores.csv — Raw MQM scores from three raters

## Corpus
Awta Kurdish–English benchmark (Ahmadi & Masoud, 2020)

## Model
TranslateGemma 4B (Finkelstein et al., 2026)

## Key Findings
- Pooled improvement: +5.67 MQM points (Welch t = 2.58, p = .023, Cohen's d = 0.88)
- Connotative and Formal-Aesthetic exceeded the MDC95 threshold

## Contact
[your email]