# Environment Setup

Get your development environment ready for computer vision research.

## Prerequisites

- A computer with macOS, Linux, or Windows
- Basic familiarity with the command line
- ~10GB free disk space

## Overview

This guide will help you set up:
1. Python (via conda or pyenv)
2. Virtual environment management
3. Essential CV libraries (PyTorch, OpenCV, etc.)
4. Jupyter notebooks for experimentation
5. Git for version control

## Directory Contents

```
02_environment_setup/
├── README.md          ← You are here
└── tutorial.ipynb     ← Step-by-step setup guide
```

## Quick Start

If you're experienced, here's the minimal setup:

```bash
# Create conda environment
conda create -n cv-research python=3.10
conda activate cv-research

# Install core packages
pip install torch torchvision
pip install opencv-python
pip install numpy matplotlib jupyter
pip install scikit-learn scikit-image
```

For detailed instructions with explanations, work through the tutorial notebook.

## Verifying Your Setup

After setup, you should be able to run:

```python
import torch
import cv2
import numpy as np

print(f"PyTorch: {torch.__version__}")
print(f"CUDA available: {torch.cuda.is_available()}")
print(f"OpenCV: {cv2.__version__}")
```

## Next Steps

Once your environment is ready, move on to:
- **[03 — Python & NumPy Basics](../03_python_numpy_basics/)** — Review essential Python skills
