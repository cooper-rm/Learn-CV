# Image Classification

Assign a single label to an entire image. This is the conceptual starting point for most of modern computer vision.

## Prerequisites

Before diving into this topic, make sure you've completed:

1. **[Getting Started](../01_getting%20started/)** — Environment setup, Python/NumPy basics, OpenCV fundamentals

## Overview

Image classification is the task of assigning a predefined label to an image based on its visual content. Given an input image, the model outputs a probability distribution over possible classes.

**Key questions this topic addresses:**
- How do we represent images for machine learning?
- What makes a good visual feature?
- How do CNNs learn hierarchical representations?
- How do we evaluate classification performance?

## Directory Contents

```
02_classification/
├── README.md          ← You are here
└── tutorial.ipynb     ← Hands-on classification tutorial
```

## Key Concepts

- Feature extraction (traditional vs. learned)
- Convolutional Neural Networks (CNNs)
- Transfer learning and fine-tuning
- Data augmentation
- Evaluation metrics (accuracy, precision, recall, F1, confusion matrix)

## Suggested Path

After completing this topic, consider moving to:
- **[03 — Localization](../03_localization/)** — Add spatial reasoning to classification
- **[04 — Object Detection](../04_object_detection/)** — Detect multiple objects

## References

- Krizhevsky et al. (2012). *ImageNet Classification with Deep Convolutional Neural Networks*
- He et al. (2016). *Deep Residual Learning for Image Recognition*
