# Next Generation Reservoir Computing (NGRC)

This repository implements the **Next Generation Reservoir Computing (NGRC)** framework for modeling and predicting chaotic dynamical systems.

The methodology follows:  
> Gauthier et al., *Next Generation Reservoir Computing*, Nature Communications (2021)



## Overview

The NGRC approach is applied to:

- **Lorenz 63 system**
- **Double Scroll system**

For each system, we evaluate:
- Short-term prediction accuracy  
- Long-term dynamical behavior  
- Qualitative agreement via return maps  



## Notebooks

- [Lorenz63_NGRC_Model.ipynb](notbook/Lorenz63_NGRC_Model.ipynb)  
  NGRC model construction and prediction (Lorenz system)

- [Lorenz63_NGRC_Model_Return_Map.ipynb](notbook/Lorenz63_NGRC_Model_Return_Map.ipynb)  
  Return map analysis (Lorenz system)

- [DoubleScrollNVAR-RK23.ipynb](notbook/DoubleScrollNVAR-RK23.ipynb)  
  NGRC model construction and prediction (Double Scroll system)


- [DoubleScrollNVAR-RK23_Return_Map.ipynb](notbook/DoubleScrollNVAR-RK23_Return_Map.ipynb)  
  Return map analysis (Double Scroll system)



## Key Idea

NGRC replaces traditional reservoirs with nonlinear feature expansions (NVAR), enabling efficient learning of chaotic dynamics using linear regression.



## Evaluation

Model performance is assessed using:
- NRMSE (prediction accuracy)  
- Attractor reconstruction  
- Return map comparison of successive maxima  



## Reference

Gauthier et al., *Next Generation Reservoir Computing*, Nature Communications (2021)  
https://arxiv.org/pdf/2106.07688