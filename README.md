# StiffNet-Benchmark
Benchmark problems/datasets for learning stiff multi-physics multi-scale systems using physics-informed machine learning.

Numerical stiffness refers to the challenges in numerically solving systems with widely spaned time/spatial scales. Most complex multi-physics multi-scale systems are numerically stiff, for example, the equations describing the reaction-diffusion in energy conversion, pollution transportation in the atmosphere, and gene/proteins/cell interactions in biological systems. While physics-informed machine learning, such as Physics-Informed Neural Network, Neural Ordinary Differential Equations, Deep Operator Learning, have shown success in many non-stiff systems, it has been shown the stiffness could fail many physics-informed machine learning algorithms. However, it is usually a painful process to prepare the datasets for stiff problems using classical numerical methods due to the nature of multi-physics, and each problem requires specific domain knowledge. This repository aims to ease the data/model preparation stage by formulating a collection of benchmark tasks for testing the performance of new algorithms on physics-informed machine learning in stiff systems.

# RoadMap

## Candidate Problems

> Problems refer to experimental/numerical datasets for stiff problems.

> For numerical problems, problems will appear as codes relying on open-source packages with detailed instructions for generating dataset.

### Ordinary Differential Equations

* ROBER (Python/Julia): A classical simple yet challanging benchmarks for stiff solvers.

* POLLU (Python/Julia): A classical simple yet challanging benchmarks for stiff solvers.

* Pyrolysis of Propane {Combustion | rely on Cantera} {Coming Soon}: A strong stiff system from the field of combustion.

### Partial Differential Equations

* RUSS (Julia): A classical simple yet challanging benchmarks for stiff solvers.

* One-dimensional Non-premixed Flame {Combustion | rely on Cantera} {Comming Soon}: A strong stiff system from the field of combustion.

## Candidate Machine Learning APIs

### Physics-Informed Neural Network (PINN)

E.g., https://github.com/DENG-MIT/Stiff-PINN

### Neural Ordinary Differential Equations (NODE)

E.g., https://github.com/DENG-MIT/StiffNeuralODE

### (Physics-Informed) DeepONet

### (Physics-Informed) Fourier Neural Network

# Relevent Links

### SciML Benchmarks
