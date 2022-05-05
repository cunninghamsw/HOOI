# HOOI
Tensor Decomposition
This is a python implementation of the HOOI algorithm as described by: 
Sheehan, S. and Saad, Y. (2007). Higher Order Orthogonal Iteration of Tensors (HOOI) and its Relation to PCA and GLRAM. Proceedngs of the 2007 SIAM International Conference on Data Mining.

The algorithm operates through successive least squares minimisation of separate tensors. The implementation unfortunately only works for 3D tensors. It would also greatly benefit from a sparse tensor implementation since it is memory intensive.
