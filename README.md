# Koopman Spectral analysis
## Introduction
Koopman Spectral analysis is an emerging non linear data analysis method which is used for Sequence modeling. After thoroughy going through several research work, there has been an attempt to give an idea about the Koopman analysis in a simple way. 

<img src="./mimages.png">

Koopman operator idea is very much similar to the Kernel methods. For any non linear dynamics in a particular space, there exists some linear space where the dynamics behave linearly. One small example is given in the above figure. One of the powerful practical use of Koopman operator is Dynamic Mode Decomposition(DMD) [1].

## Practical Koopman Operator-DMD

DMD is a data-driven method used in many areas like power grids, epidemiology, fluid dynamics etc. DMD is capable of capturing dynamics of the system using basic linear algebra concepts. This makes DMD a simple tool to understand the capabilities of Koopman operator. Before we get inot the DMD algorithm formulation. Lets chec out Sigular Value Decomposition(SVD) which will be the crux of DMD algorithm.

### The heart-SVD
SVD is a matrix deecomposition method used for dimentionality reduction. It's concept is similar to eigen decomposition.  


<img src="svd.png" width="400">
