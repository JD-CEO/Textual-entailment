# Textual Entailment Analysis with SNLI Dataset

[[Dataset](https://nlp.stanford.edu/projects/snli/)] 
[[Paper](`Recognizing Textual Entailment in SNLI dataset-report.pdf`)] 

**Course Project | Data Science Course | Shahid Beheshti University | 2023-2024**

## 🎯 Project Goal
This project aims to investigate textual entailment relationships through comprehensive analysis of the SNLI dataset, focusing on:
- Understanding linguistic patterns in premise-hypothesis pairs
- Identifying key statistical characteristics of textual entailment
- Developing analytical frameworks for relationship classification
- Establishing baseline metrics for future research comparisons

## 📚 Dataset Overview
**Stanford Natural Language Inference (SNLI) Corpus**  
_550,153 human-annotated sentence pairs_

### Key Characteristics:
- **Triple Classification**: Entailment/Contradiction/Neutral
- **Lexical Diversity**:
  - 28,124 unique tokens
  - 15.2 avg. words per sentence
- **Balance Analysis**:
  - Entailment: 33.3%
  - Contradiction: 32.9% 
  - Neutral: 33.8%

## 🔍 Analytical Focus
### 1. Structural Analysis
- Sentence length distributions
- POS tag frequency comparisons
- Lexical overlap metrics
- N-gram pattern extraction

### 2. Semantic Relationships
- WordNet-based similarity scores
- Semantic role labeling patterns
- Co-reference resolution cases
- Negation impact analysis
  
## 🔍 Key Analytical Findings

| Analysis Dimension       | Metric                     | Value         |
|---------------------------|----------------------------|---------------|
| **Lexical Overlap**       | Mean Jaccard Similarity     | 0.28 ± 0.12   |
| **Structural Complexity** | Average Parse Tree Depth   | 5.82          |
| **Semantic Distance**      | Word2Vec Cosine Similarity | 0.61          |

## 📂 Repository Structure
```
├── data/
├── analysis/notebooks/
│   ├── lexical_analysis/   # Overlap metrics
│   ├── semantic_analysis/ # Word embeddings
│   └── statistical_tests/ # Hypothesis testing
└── report/Recognizing Textual Entailment in SNLI dataset-report.pdf              # Final project PDF
```
## 📚 References
- SNLI Original Paper: Bowman et al. (2015)
- Linguistic Theory of Entailment: Dagan et al. (2006)
- Modern NLP Analysis Techniques: Jurafsky & Martin (2023)
