# Beyond Binary: Ensuring Fairness in Gender Classification Algorithms

This repository contains the code and resources for the paper _"Beyond Binary: Ensuring Fairness in Gender Classification Algorithms"_.

## Abstract

This paper addresses the critical issue of fairness in gender classification algorithms, proposing methodologies to enhance algorithmic accountability and reduce gender bias. Three distinct gender classification models are developed using the publicly available FairFace dataset, along with a newly curated BalancedFace dataset aimed at rectifying demographic and gender biases present in existing datasets. A comprehensive analysis evaluates the fairness of these models using metrics such as disparate impact, recall parity, and classification accuracy across gender and demographic groups.

The results indicate that the model trained on the BalancedFace dataset significantly improves fairness in gender prediction, outperforming models trained on FairFace. This demonstrates the effectiveness of balanced dataset curation in creating ethical AI systems.

## 📦 Datasets

The following datasets were used in this research:

- **BalancedFace** (`Balanced.zip`): A curated dataset to mitigate demographic and gender bias  
  🔗 [Download via Google Drive](https://drive.google.com/file/d/1V_nlsaPWc9H2qEiCVIxASzHUwEvl0nJc/view?usp=sharing)  
  👉 Optional direct link:  
  `https://drive.google.com/uc?export=download&id=1V_nlsaPWc9H2qEiCVIxASzHUwEvl0nJc`

- **FairFace** (`Original_Dataset.zip`): The original publicly available dataset  
  [FairFace GitHub](https://github.com/joojs/fairface)

- **Trained Models**:  
  🔹 `Savedmodels.zip` – contains pre-trained weights for all experiments

## 🧪 Usage

To replicate the results and experiments from the paper:

1. **Clone the repository**
   ```bash
   git clone https://github.com/TadesseK/beyond-binary.git
   cd beyond-binary
