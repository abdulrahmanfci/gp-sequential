# gp-sequential

This is the repository for "Estimating Treatment Effect using Gaussian Process for Population-scale Simulations" paper submitted to Winter Simulation Conference (WSC'24)


## Abstract
Agent-based simulation allows us to understand epidemic dynamics better and help build public health policies. FRED (A Framework for Reconstructing Epidemiological Dynamics) is an agent-based modeling system 
with a geospatial perspective using a synthetic population that is constructed based on the U.S. census data. However, as the number of treatment effects to estimate increases, the required computational cost to 
conduct these simulation runs rises significantly. Therefore, we look for a metamodel to estimate the treatment effect instead of the actual model. Gaussian process proved its capability of accurate estimation in 
different fields, and with the help of sequential optimal design, it selects the most critical samples. In this paper, we show that the Gaussian process (GP) regression  can accurately learn an estimate of treatment 
effects with as few samples as possible compared to the benchmark method. As a demonstration of its performance, we show the GP regression results for two  different epidemics.
