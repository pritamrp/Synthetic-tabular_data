# Synthetic Tabular Data Generation Project  
**BA890: Analytics Practicum**

## Overview
This project explores and compares different approaches to generating **synthetic tabular data**, focusing on two main models: **CTGAN** and **REaLTabFormer**. Using an online gaming behavior dataset, we evaluate these models' effectiveness in producing high-quality, privacy-preserving synthetic data.

## Dataset
The project utilizes the **"Predict Online Gaming Behaviour Dataset"**, which contains player behavior and demographic information.  
**Source**: [Kaggle - Online Gaming Behavior Dataset](https://www.kaggle.com)

## Models Implemented

### **CTGAN (Conditional Tabular GAN)**  
- A specialized GAN architecture for tabular data  
- **Source**: [SDV Developers GitHub](https://github.com/sdv-dev)

### **REaLTabFormer**  
- A transformer-based approach for realistic tabular data generation  
- **Source**: [World Bank GitHub](https://github.com/WorldBank)

## Key Findings
- **REaLTabFormer** demonstrated superior performance compared to **CTGAN**, particularly in:  
  - Preserving complex relationships within the data  
  - Generating more realistic synthetic samples  
  - Maintaining data quality and integrity  

## Project Structure
```plaintext
text
├── notebooks/
│   ├── CTGAN_implementation.ipynb
│   └── REaLTabFormer_implementation.ipynb
├── data/
│   ├── raw/
│   └── processed/
└── README.md
```
## Technical Notes
- The **transformer model** was executed in a separate notebook due to computational requirements.  
- Both models were evaluated using **standard metrics for synthetic data quality**.

## Author
**Pritam Pandit**

## References
- **SDV Developers.** (2023). [CTGAN: Conditional Tabular GAN](https://github.com/sdv-dev).  
- **World Bank.** (2023). [REaLTabFormer: Realistic Tabular Data Transformer](https://github.com/WorldBank).  

**Note**: For detailed implementation and results, please refer to the individual notebooks in the repository.

