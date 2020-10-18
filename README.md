# A_Comparison_Between_Two_Manifold_Techniques
Author : Furrer Stanislas and Carvalho Luis
Date   : 01.06.2020

This paper comprehensively reviews and discusses LLE and its modified version. Their stability with various data and hyper parameters is depicted as well as their performance of topology preservation and classification.

Related Papers :
* [1] “Locally Linear Embedding”, Roweis, S.T., and L.K. Saul (2000)
* [2] “Modified Linear Embedding”, Zhang, Zhenyue & Wang, Jing. (2006)


The machine learning techniques utilized in this study were:
* Locally Linear Embedding
* Modified Locally Linear Embedding
* K Nearest Neighbors
* Convolutional Neural Network

The Evaluation Criteria utilized in this study were
* Spearman’s Rho topology preservation [3]
* Residual variance [4]
* Classification reate reduction [5]
* f1-score

\begin{equation}\rho_{S p}=1-\frac{6 \sum_{i=1}^{T}\left(r_{x}(i)-r_{y}(i)\right)^{2}}{T^{3}-T}\end{equation}
