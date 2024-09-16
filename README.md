# Beyond Binary: Ensuring Fairness in Gender Classification Algorithms

This repository contains the code and resources for the paper "Beyond Binary: Ensuring Fairness in Gender Classification Algorithms"

## Abstract

This paper addresses the critical issue of fairness in gender classification algorithms, proposing methodologies to enhance algorithmic accountability and reduce gender bias. Three distinct gender classification models are developed using the publicly available FairFace datasets, along with a newly curated BalancedFace dataset aimed at rectifying demographic and gender biases present in existing datasets. A comprehensive analysis evaluates the fairness of these models using metrics such as disparate impact, recall parity, and classification accuracy across gender and demographic groups.

The results indicate that the model trained on the BalancedFace dataset significantly improves fairness in gender prediction, outperforming models trained on FairFace. This demonstrates the effectiveness of balanced dataset curation in creating ethical AI systems.

## Datasets

The following datasets were used in this research:

- **BalancedFace**: `Balanced.zip` - A curated dataset aimed at rectifying demographic and gender biases.
- **FairFace**: `Original_Dataset.zip` - A publicly available dataset with diverse racial and gender categories.

The trained models used in this research are available for download:

- `Savedmodels.zip`

## Usage

To replicate the results and experiments from the paper, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/username/beyond-binary.git
