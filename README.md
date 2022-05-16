# MATLAB Code from Numerical Experiments in Paper *"A fast method to estimate the Moore-Penrose inverse for well-determined numerical rank matrices based on the Tikhonov regularization"*

**Paper Title:** A fast method to estimate the Moore-Penrose inverse for well-determined numerical rank matrices based on the Tikhonov regularization

**Author:** Pablo Soto-Quiros (https://www.tec.ac.cr/juan-pablo-soto-quiros)

**Institute:** Instituto Tecnológico de Costa Rica (https://www.tec.ac.cr/)

**Email:** jusoto@tec.ac.cr

**Description:** This repository contains the MATLAB code for numerical experiments presented in the paper "*A fast method to estimate the Moore-Penrose inverse for well-determined numerical rank matrices based on the Tikhonov regularization*". This paper was submitted to be published in proceedings of the **Journal of Computational Science** (https://www.journals.elsevier.com/journal-of-computational-science). This paper presents a new method to estimate the Moore-Penrose inverse. The proposed method is based on Tikhonov regularization, which requires computing all positive singular values of a matrix of dimension<img src="https://latex.codecogs.com/gif.latex?m\times n " /> . Additionally, we present an efficient and accurate procedure to estimate these singular values, which assumes that <img src="https://latex.codecogs.com/gif.latex?A^*A " />  (if <img src="https://latex.codecogs.com/gif.latex? m\geq n " /> ) and <img src="https://latex.codecogs.com/gif.latex?AA^* " /> (if <img src="https://latex.codecogs.com/gif.latex? m\leq n " />) are well-determined numerical rank matrices.  Besides, we show an application of the proposed method in the solution of linear discrete well-posed problems. Finally, numerical simulations are presented to illustrate the advantages of the new method. Moreover, we show that the execution time associated with this new technique is less than methods mentioned in the literature. Computational experiments to measure execution time and speedup confirmed the efficiency of the proposed method.
