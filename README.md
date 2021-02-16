# Training of machine learning models for COVID-19 dataset
# Installation:
# Requirements:
- Anaconda
- Python 3.5
- Numpy
- Scipy
- Sci-kit learn
- Pandas
- matplotlib

# Models are trained based on two output parameters
- Case Fatality Ratio (CFR)
- CFR = Cumulative number of death / Cumulative number of cases

- COVID-19 Spreading Ratio (CSR)
- CSR = Cumulative number of cases / Total population

# Data collection strategy
- Data are collected from 57 locations from all over the world
- These locations are chosen so that the density of 65+ aged population are evenly distribu  

# Input dataset:
- We have total 22 input features where some parameters infl

# Results:
# Training Convergence [CFR]: 
![TrainConvg](Results/Figures/CFRLossVal.png?raw=true "Title")
# Training Convergence [CSR]: 
![TrainConvgCSR](Results/Figures/CSRLossVal.png?raw=true "Title")
# Parameter correlation: 
![Corr](Results/Figures/CorrCoefficient.png?raw=true "Title")
