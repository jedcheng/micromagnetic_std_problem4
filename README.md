# micromagnetic_std_problem4 


A solver to solve the micromagnetic standard problem 4

https://www.ctcms.nist.gov/~rdm/mumag.org.html



## Notebooks
Replicates the standard problem 4 in 2D
[std_problem4_torch.ipynb](std_problem4_torch.ipynb)

Replicates the standard problem 4 in 3D
[std_problem4_torch_3D_Solver.ipynb](std_problem4_torch_3D_Solver.ipynb)

Replicates the standard problem 4 in 3D but the thickness is doubled
[std_problem4_torch_3D_Solver_Double_Thickness.ipynb](std_problem4_torch_3D_Solver_Double_Thickness.ipynb) 


Note:
Use the first notebook to build a 2D solver and the third notebook to build a 3D solver. The second notebook is just a 3D solver for a 2D problem.


## Running the code
It is recommended to run the code in Google Colab. The notebooks are already configured to run in Google Colab and it does not require much time to run the code in Google Colab using GPU.


## Translated from:

Zhu, Ru. "Accelerate micromagnetic simulations with GPU programming in MATLAB." arXiv preprint arXiv:1501.07293 (2015).
https://arxiv.org/ftp/arxiv/papers/1501/1501.07293.pdf

https://github.com/cygnusc/mumag.matlab/blob/master/stdprob4aGPU.m

to Python and Pytorch



## Inprogress
1. Implement Slonczewski and Zhang-Li spin transfer torque
2. Translated the code to SYCL in DPC++
