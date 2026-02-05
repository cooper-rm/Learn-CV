# Learn-CV

Welcome to **Learn-CV**, Regis University's self-sustaining learning ecosystem for Computer Vision research.

## Purpose

This repository is designed to onboard new MSDS students into the Computer Vision Research Group. Our goal is to get you from zero to productive research as quickly as possible.

## Getting Started

**New to the group?** Start here:

1. **[Start Here](topics/01_getting%20started/01_overview/START_HERE.ipynb)** — Overview of computer vision and the repository
2. **[Environment Setup](topics/01_getting%20started/02_environment_setup/)** — Set up your development environment
3. **[Python & NumPy](topics/01_getting%20started/03_python_numpy_basics/)** — Review essential skills
4. **[OpenCV Fundamentals](topics/01_getting%20started/04_opencv_fundamentals/)** — Image processing basics
5. **[Git Fundamentals](topics/01_getting%20started/05_git_fundamentals/)** — Version control and collaboration

Then dive into topics based on your research interests!

## Repository Structure

```
Learn-CV/
├── topics/
│   ├── 01_getting started/          # Start here!
│   │   ├── 01_overview/
│   │   ├── 02_environment_setup/
│   │   ├── 03_python_numpy_basics/
│   │   ├── 04_opencv_fundamentals/
│   │   └── 05_git_fundamentals/
│   ├── 02_classification/           # Image classification
│   ├── 03_localization/             # Object localization
│   ├── 04_object_detection/         # Multi-object detection
│   ├── 05_segmentation/             # Semantic/instance segmentation
│   ├── 06_pose_estimation/          # Keypoint detection
│   ├── 07_action_recognition/       # Video understanding
│   ├── 08_generative_models/        # GANs, VAEs, diffusion
│   ├── 09_visual_slam/              # Localization & mapping
│   ├── 10_scene_understanding/      # Scene graphs, VQA
│   ├── 11_facial_recognition/       # Face detection & recognition
│   ├── 12_geolocation/              # Visual place recognition
│   ├── 13_anomaly_detection/        # Anomaly detection
│   ├── 14_vision_rl/                # Vision-based RL
│   ├── 15_embeddings_similarity/    # Image embeddings & search
│   ├── 16_vision_transformers/      # ViT, CLIP, SAM
│   └── 17_self_supervised_learning/ # SimCLR, DINO, MAE
├── CONTRIBUTING.md
├── COLLABORATORS.md
└── TODO.md
```

Each topic contains:
- `README.md` — Overview, prerequisites, and suggested learning path
- `tutorial.ipynb` — Hands-on tutorial with exercises
- `project_template.ipynb` — Template for your own research project

## Learning Path

Topics build on each other. Each README lists prerequisites, but here's the general flow:

```
Getting Started
     ↓
Classification (02) ──────────────────────→ Embeddings & Similarity (15)
     ↓                                                   ↓
Localization (03) → Object Detection (04) → Segmentation (05)
     ↓                                            ↓
Pose Estimation (06) ─────────────────────→ Action Recognition (07)

Generative Models (08) ←──────────────────→ Anomaly Detection (13)

Visual SLAM (09) ←→ Geolocation (12) ←→ Scene Understanding (10)

Facial Recognition (11) ←─────────────────→ Embeddings & Similarity (15)

Vision Transformers (16) ← [Modern architectures: ViT, CLIP, SAM, DINOv2]
         ↓
Self-Supervised Learning (17) ← [Learn without labels: SimCLR, MAE]

Vision-Based RL (14) ← [Capstone topic, combines many areas]
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding content.

## Research Group Members

See [COLLABORATORS.md](COLLABORATORS.md) for a list of individuals who helped make this possible.
