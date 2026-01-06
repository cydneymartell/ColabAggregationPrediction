# Google Colab Notebook to Predict and Engineer Aggregation Resistance

<p align="left">
  <a href="https://www.biorxiv.org/content/10.1101/2025.11.11.687847v1">
    <img src="https://img.shields.io/badge/Paper-bioRxiv-green?style=for-the-badge" alt="bioRxiv Paper">
  </a>
  &nbsp;
  <a href="https://hf.co/collections/cmartell/martell-et-al-2025-aggregation-models-and-datasets">
    <img src="https://img.shields.io/badge/%F0%9F%A4%97-Hugging%20Face-red?style=for-the-badge" alt="Hugging Face Collection">
  </a>
  &nbsp;
  <a href="https://colab.research.google.com/drive/1KNWvGji8myBuI2uzOQ-O_xtEf0Q4pvbm?usp=sharing">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab" style="height:28px">
  </a>
</p>

## Motivation 

This repository contains scripts for predicting aggregation using the models and data from the manuscript [*Global Analysis of Aggregation Determinants in Small Protein Domains*] (https://www.biorxiv.org/content/10.1101/2025.11.11.687847v1). The goal of this project is to enable others to predict protein aggregation to engineer aggregation resistance using the fine-tuned SaProt mdodels. 

The Colab notebook can be accessed from https://colab.research.google.com/drive/1KNWvGji8myBuI2uzOQ-O_xtEf0Q4pvbm?usp=sharing.  

---

## Key Features 

  - Predict aggregation for 50 &deg;C, 75 &deg;C or pH 4 aggregation for a single or multiple protein sequences. 
  - Perform deep mutational scan predictions for a protein of interest.
  - Integrate stability predictions from ThermoMPNN to compare predicted aggregation and stability effects of single point mutations. 

---
## Acknowledgements 

- Portions of this workflow incorporate scripts and adapted functions from SaProtHub (Su et al., 2024), which provides a framework for training and using fine-tuned SaProt models.
  > Su, J., Li, Z., Han, C., Zhou, Y., Shan, J., Zhou, X., Ma, D., The OPMC, Ovchinnikov, S., & Yuan, F. (2024). SaProtHub: Making Protein Modeling Accessible to All Biologists.

- This workflow also incorporates scripts from ThermoMPNN to predict stability changes.
  > Dieckhaus, H., Brocidiacono, M., Randolph, N. Z., & Kuhlman, B. (2024). Transfer learning to leverage larger datasets for improved prediction of protein stability changes. Proceedings of the National Academy of Sciences, 121(6), e2314853121. https://doi.org/10.1073/pnas.2314853121
  
