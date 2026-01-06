# Google Colab Notebook to Predict and Engineer Aggregation Resistance
<a href="https://www.biorxiv.org/content/10.1101/2025.11.11.687847v1"><img src="https://img.shields.io/badge/Paper-bioRxiv-blue" style="max-width: 100%;"></a>
<a href="https://hf.co/collections/cmartell/martell-et-al-2025-aggregation-models-and-datasets"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-red?label=Martell et al 2025" style="max-width: 100%;"></a>
<a href="https://colab.research.google.com/drive/1KNWvGji8myBuI2uzOQ-O_xtEf0Q4pvbm?usp=sharing"><img src="Figure/colab-badge.svg" style="max-width: 100%;"></a>

This repository contains scripts for predicting aggregation using the models and data from the manuscript [Global Analysis of Aggregation Determinants in Small Protein Domains] (https://www.biorxiv.org/content/10.1101/2025.11.11.687847v1). The goal of this project is to enable others to predict protein aggregation to engineer aggregation resistance. 

The Colab notebook can be accessed from https://colab.research.google.com/drive/1KNWvGji8myBuI2uzOQ-O_xtEf0Q4pvbm?usp=sharing.  This notebook can be used to predict aggregation for 50 &deg;C, 75 &deg;C or pH 4 aggregation for a single or multiple protein sequences. Additionally for a protein of interest predictions can be made and plotted across the deep mutational scan. We also incorporated stability predictions from ThermoMPNN to compare predicted aggregation and stability effects of single point mutations. 


##### Portions of this workflow incorporate scripts and adapted functions from SaProtHub (Su et al., 2024), which provides a framework for training and using fine-tuned SaProt models.

##### Su, J., Li, Z., Han, C., Zhou, Y., Shan, J., Zhou, X., Ma, D., The OPMC, Ovchinnikov, S., & Yuan, F. (2024). SaProtHub: Making Protein Modeling Accessible to All Biologists.

##### This workflow also incorporates scripts from ThermoMPNN to predict stability changes.

##### Dieckhaus, H., Brocidiacono, M., Randolph, N. Z., & Kuhlman, B. (2024). Transfer learning to leverage larger datasets for improved prediction of protein stability changes. Proceedings of the National Academy of Sciences, 121(6), e2314853121. https://doi.org/10.1073/pnas.2314853121
  
