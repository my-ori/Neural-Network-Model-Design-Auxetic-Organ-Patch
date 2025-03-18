# Mechanics and Design of Metastructured Auxetic Patches with Bio-inspired Materials
## This code is related to the journal article: 10.48550/arXiv.2501.06233

## Abstract  
Metastructured auxetic patches, characterized by negative Poisson's ratios, offer unique mechanical properties that closely resemble the behavior of human tissues and organs. As a result, these patches have gained significant attention for their potential applications in organ repair and tissue regeneration. This study focuses on neural networks-based computational modeling of auxetic patches with a sinusoidal metastructure fabricated from silk fibroin, a bio-inspired material known for its biocompatibility and strength. The primary objective of this research is to introduce a novel, data-driven framework for patch design. To achieve this, we conducted experimental fabrication and mechanical testing to determine material properties and validate the corresponding finite element models. Finite element simulations were then employed to generate the necessary data, while greedy sampling, an active learning technique, was utilized to reduce the computational cost associated with data labeling. Two neural networks were trained to accurately predict Poisson's ratios and stresses for strains up to 15\%, respectively. Both models achieved $R^2$ scores exceeding 0.995, which indicates highly reliable predictions. Building on this, we developed a neural network-based inverse design model capable of generating multiple optimal metastructure designs tailored to specific mechanical properties. For single-design cases, the design model achieved a mean absolute error (MAE) of less than 0.005 for Poisson’s ratio and less than 1 kPa for stress across three test examples. For multiple-design cases, the MAEs remained below 0.03 for Poisson’s ratio and below 1 kPa for stress, demonstrating superior performance compared to traditional optimization methods, such as genetic algorithms, by providing more efficient and precise design solutions. The proposed framework represents a significant advancement in the design of bio-inspired metastructures for medical applications, paving the way for future innovations in tissue engineering and regenerative medicine.

## Repository Structure  

This repository contains:  

**A Jupyter Notebook (.ipynb)** for running the predictive and design models.  

**Three corresponding datasets** are required for training and testing the models.

## Code Breakdown

**Sections 1-4:** Training process for the predictive models.  

**Subsequent Sections:** Implementation of the inverse design model.


## Contact  
For any issues or questions related to the code, feel free to contact the author:  
**Yingbin Chen, yingbin-chen@uiowa.edu**  
