This repository contains simulation codes for the paper: **Adaptive Quantization Resolution and Power Control for Federated Learning over Cell-free Networks**. Check out the [here](https://arxiv.org/abs/2412.10878) for more details.

# 📡 Federated Learning over Cell-free massive MIMO Networks: Adaptive Quantization & Power Control  

## 📖 Description  
This repository contains the implementation of our research on optimizing Federated Learning (FL) over **Cell-Free massive MIMO (CFmMIMO) networks**.  
We propose a **co-optimized physical layer and FL framework** that mitigates the straggler effect through:  
- **Adaptive Mixed-Resolution Quantization** – Prioritizing essential gradient updates with higher precision.  
- **Dynamic Uplink Power Control** – Managing user rates for efficient communication.  

📄 **[Paper](https://arxiv.org/abs/2412.10878)**  

## 🚀 Key Contributions  
✔️ Reduces **communication overhead by 93%** while maintaining FL accuracy.  
✔️ **75% lower overhead** and **10% higher test accuracy** than AQUILA, Top-q, and LAQ.  
✔️ Evaluated on **CIFAR-10, CIFAR-100, and Fashion-MNIST** datasets.  



## 📂 Code Structure  

- **`APLocation_Generation.ipynb`** – Generates access point locations for CFmMIMO simulation.  
- **`AQUILA.ipynb`** – Implements AQUILA quantization for comparison.  
- **`CFmMIMO + quantization + FL CIFAR10 + power control.ipynb`** – Combines FL, quantization, and power control on CIFAR-10.  
- **`CIFAR10_FedAvg_Quantization for GC2024.ipynb`** – Implements FedAvg with quantization for CIFAR-10.  
- **`FL cifar100 + OLD_CFmMIMO + quantization + power control.ipynb`** – FL with CFmMIMO settings on CIFAR-100.  
- **`LAQ.ipynb`** – Implements the LAQ quantization scheme for comparison.  
- **`Top-q percent.ipynb`** – Implements Top-q quantization method for comparison.  
- **`fashion_mnist iid + FL + quantization.ipynb`** – FL with quantization on IID Fashion-MNIST dataset.  
- **`fashion_mnist non-iid + FL + quantization.ipynb`** – FL with quantization on non-IID Fashion-MNIST dataset.  
- **`functionRlocalscattering.ipynb`** – Computes local scattering functions for CFmMIMO.  
- **`optimizing the min max .ipynb`** – Optimizes min-max latency for FL over CFmMIMO.  
- **`pilot_assignment.ipynb`** – Implements pilot assignment strategy for CFmMIMO.  
- **`solving min max latency.ipynb`** – Solves optimization for minimizing max latency.  
- **`solving with linear programming.ipynb`** – Solves optimization problem using linear programming.  

