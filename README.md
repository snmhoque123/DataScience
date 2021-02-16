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
- We have divided the locations into 5 categories where the locations in each category have the similar density of 65+ aged population.  
- Distribution of population density over 65+ aged people: 
![pop_65+](Results/Figures/Pop_65+_category.png?raw=true "Title")

# Input dataset:
- We have total 22 input features where some parameters influences CSR and ot

# Results:
# Training Convergence [CFR]: 
![TrainConvg](Results/Figures/CFRLossVal.png?raw=true "Title")
# Training Convergence [CSR]: 
![TrainConvgCSR](Results/Figures/CSRLossVal.png?raw=true "Title")
# Parameter correlation: 
![Corr](Results/Figures/CorrCoefficient.png?raw=true "Title")
