<div align="center">

# 🚦 Traffic Light Adversarial Defense

### Adversarial Patch Attacks and Defense for YOLO-Based Traffic Light Detection

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-red)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

<img src="assets/banner.png" width="850"/>

</div>

---

## Overview

This repository contains the code and experiments for studying adversarial patch attacks and defense strategies for traffic light detection using YOLOv8.

**Features**
- PGD adversarial patch generation
- Transferability evaluation
- Defense experiments
- BSTLD and LISA dataset support

---

## Repository Structure

```text
configs/        Experiment configurations
datasets/       Dataset information
docs/           Project documentation
experiments/    Training and evaluation
patch_utils/    Shared utilities
publication/    Paper, figures, and tables
results/        Experiment outputs
scripts/        Training and evaluation scripts
```

---

## Installation

```bash
conda env create -f environment.yml
conda activate traffic-defense
pip install -r requirements.txt
```

---

## Quick Start

Train a patch

```bash
python scripts/train_patch_yolov8_fixed.py
```

Evaluate a patch

```bash
python scripts/evaluate_patch.py
```

---

## Datasets

- BSTLD
- LISA

See `datasets/README.md` for setup instructions.

---

## Citation

If you use this repository, please cite the associated publication (coming soon).

---

## License

MIT License.
