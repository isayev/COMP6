## COmprehensive Machine-learning Potential (COMP6) Benchmark Suite
This repository contains the COMP6 benchmark for evaluating the extensibility of machine-learning based molecular potentials.

##### If you use the COMP6 benchmark please cite this paper: 

Justin S. Smith, Ben Nebgen, Nicholas Lubbers, Olexandr Isayev, Adrian E. Roitberg. *Less is more: sampling chemical space with active learning*. arXiv, 2018, DOI: [arXiv:1801.09319] (https://arxiv.org/abs/1801.09319)

## Usage
Please read the README.md in the repository linked below for instructions on how to extract the COMP6 HDF5 (extention \*.h5) files. 
https://github.com/isayev/ANI1_dataset

The following paper contains a description of the file format:
https://www.nature.com/articles/sdata2017193

## Current Benchmark Results:
#### Please read https://arxiv.org/abs/1801.09319 for a detailed description of our error metrics.
#### Please contact Justin S. Smith at jussmith48@gmail.com if you'd like to add your results from the COMP6 benchmark.
##### Units: kcal/mol and kcal/mol/A (errors are NOT per atom)
##### Error key: MAE/RMSE
|   Potential        |     Energy    |   Relative Energy  |     Force     |
| ------------------ | ------------- | ------------------ | ------------- |
| ANI-1x<sup>1</sup> |  1.93/3.37    | <center>1.85/2.95</center>      |   3.09/5.29   |
| ANI-1<sup>1</sup>  |  5.01/16.94   |     3.01/6.97      |   3.70/7.13   |

##### 1) https://arxiv.org/abs/1801.09319
