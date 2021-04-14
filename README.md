# PDRP 2021
## Overview

 This is a sanbox for the physics [directed reading program](https://berkeleyphysicsdrp.wixsite.com/physicsberkeleydrp) during Spring '21. This project (including this README) is a WIP.

## Features

* An implementation of matrix product states, supporting
	- constructing one from any initial tensor and specified bond dimension
	- contraction back to a tensor of high (tensor-)rank
	- time evolving block decimation

## TODO

* TEBD
	- Add tests for 2-local interaction term
	- add visualizations
* Examples to add
	- classification [1]
	- comparing time evolution
* Other
	- add coverage

## Sources

1. [TensorNetwork for Machine Learning](https://arxiv.org/pdf/1906.06329.pdf)
1. [Towards Quantum Machine Learning with Tensor Networks](https://arxiv.org/pdf/1803.11537.pdf)
1. [Efficient classical simulation of slightly entangled quantum computations](https://arxiv.org/pdf/quant-ph/0301063.pdf)
