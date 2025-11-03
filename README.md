# Biologically-Informed Algorithms for Modeling Cattle Response  
by Hannah James (Cornell)  

## Overview  
This repository hosts the code and supporting data underlying the manuscript  
*“Biologically-informed algorithmic framework to simulate cattle responses to auditory cues in virtual fencing systems.”*  
The study integrates behavioural biology, animal-welfare science, and computational modelling to simulate how cattle (*Bos taurus*) respond to auditory cues in virtual-fencing scenarios.  

Use-cases:  
- Reproduce all analyses, figures, and tables published in the paper.  
- Apply the modelling framework to alternative cue-designs or herd settings.  
- Extend or adapt the algorithmic logic for other livestock-oriented applications.  

## Computational Environment  
The analyses and simulations were conducted in **Google Colab** using:  
- Python 3.12.12 (GCC 11.4.0, glibc 2.35)  
- NumPy 2.0.2  
- Pandas 2.2.2  
- Matplotlib 3.10.0  
- SciPy 1.16.3  

## Parameter Documentation and Supplementary Table S1  
All behavioural and acoustic parameters used in the model are documented in both the published *Supplementary Table S1* 
Each entry includes:  
- Parameter symbol and value range  
- Empirical or literature source  
- Functional–biological interpretation  
- Units or dimensionless designation  

These parameters were compiled from twenty independent validation studies and form the empirical basis for model calibration and biological interpretation.

## Citation  
If you use this code or framework, please cite:  
> James, H., Perez, M., Adams, H., Giordano, J., Peck, M., & Erickson, D. (2025). Biologically informed algorithms for modeling cattle response to auditory cues and driving simulations in virtual fencing systems. Frontiers in Animal Science, 6, Article XXXX. https://doi.org/10.3389/fanim.2025.xxxxxx


