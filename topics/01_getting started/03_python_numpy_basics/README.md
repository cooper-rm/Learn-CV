# Python & NumPy Basics

Review essential Python and NumPy skills needed for computer vision work.

## Prerequisites

- **[02 — Environment Setup](../02_environment_setup/)** — Python environment ready

## Overview

Computer vision is heavily dependent on efficient array manipulation. This section reviews:

1. Python fundamentals (functions, classes, list comprehensions)
2. NumPy array creation and manipulation
3. Broadcasting and vectorization
4. Array indexing and slicing
5. Common operations for image data

## Directory Contents

```
03_python_numpy_basics/
├── README.md          ← You are here
└── tutorial.ipynb     ← Hands-on Python/NumPy review
```

## Why This Matters

Images are represented as NumPy arrays. Understanding array operations allows you to:
- Efficiently process image data
- Debug tensor shape issues (very common!)
- Write vectorized code that runs fast
- Understand what deep learning frameworks do under the hood

## Key Concepts

- Array shapes and dimensions (H, W, C format)
- Broadcasting rules
- Vectorized operations vs. loops
- Memory layout (contiguous arrays)
- Data types (uint8, float32, etc.)

## Self-Assessment

You're ready to move on if you can:
- [ ] Create arrays with specific shapes
- [ ] Index and slice multi-dimensional arrays
- [ ] Apply operations across specific axes
- [ ] Reshape arrays without copying data
- [ ] Convert between data types

## Next Steps

After completing this section:
- **[04 — OpenCV Fundamentals](../04_opencv_fundamentals/)** — Image I/O and manipulation
