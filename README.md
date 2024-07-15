# Deep Learning Internal Class
Minimal and modular implementation of MNIST classification using PyTorch.

## How to Setup
### 1. Setup Virtual Environment
Create a new virtual environment folder named `.venv` by running the command below. Make sure the command is run within the root folder of this project.
```bash
py -m venv .venv
```

Activate the virtual environment using one of the command below according to your operating system.
```bash
# Windows
.venv/Scripts/activate

# Linux or Mac
source .venv/bin/activate
```

### 2. Install the requirements
```bash
pip install -r requirements.txt --index-url https://download.pytorch.org/whl/cu118 --no-cache-dir
```
The `index-url` arg is meant so that the PyTorch version installed is for CUDA 11.8. `no-cache-dir` ensures that it won't use the cached library from the system since most of the versions in here are new and probably not in your system.

## Repository Content
### Jupyter Notebook

### Python Scripts

## Reference
### Theoretical
- [CMU's Deep Learning System Course](https://dlsyscourse.org/) 
  - [Automatic Differentiation](https://www.youtube.com/watch?v=56WUlMEeAuA)
  - [Neural Network Abstractions](https://www.youtube.com/watch?v=fzKNkS_5E6U)
- [Andrej Karpathy's Micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0)

### Implementation
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
  - [Dataloaders](https://pytorch.org/tutorials/beginner/basics/data_tutorial.html)
  - [Model Building](https://pytorch.org/tutorials/beginner/basics/buildmodel_tutorial.html)
  - [Optimization (Training Loop)](https://pytorch.org/tutorials/beginner/basics/optimization_tutorial.html)
- Utilities
  - [Training Loop Progress Bar](https://aladdinpersson.medium.com/how-to-get-a-progress-bar-in-pytorch-72bdbf19b35c)