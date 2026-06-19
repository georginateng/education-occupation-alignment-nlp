# Educational and Occupational Competencies in a Shared Semantic Space

This repository contains replication materials for the NLP Course Paper:

**Educational and Occupational Competencies in a Shared Semantic Space: Evidence from Korean University Curricula and Occupational Profiles**

## Overview

This project examines semantic relationships between educational competency descriptions and occupational competency descriptions in South Korea. University curriculum learning objectives and occupational profiles are represented using multilingual Sentence-BERT embeddings and compared using cosine similarity.

The analysis focuses on four disciplinary domains:

- Computing
- Statistics/Data Science/Artificial Intelligence
- Business/Economics
- Industrial Engineering

## Data Sources

The educational competency corpus is based on the Korea Education and Research Information Service (KERIS) University Curriculum and Syllabus Dataset, accessed through the National Public Data Portal.

The occupational competency corpus is based on occupational overview descriptions from the CareerNet Occupational Encyclopedia, maintained by the Korea Research Institute for Vocational Education and Training (KRIVET).

Processed data files used for analysis are included in the `data/` folder.

## Repository Structure

```text
code/
  NLP_education_occupation_analysis.ipynb       # Main analysis notebook

data/
  domain_corpora.csv   # Cleaned educational competency data
  occupation_clean.csv  # Occupational competency descriptions

figures/
  heatmap.png    # Main similarity heatmap
