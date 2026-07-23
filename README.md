# Traffic Light Adversarial Defense

> Adversarial patch attacks, transferability analysis, and defense strategies for traffic light detection using YOLOv8.

---

## Overview

This repository contains the code, experiments, and publication materials for research on adversarial patch attacks against traffic light detection systems. The project investigates both attack effectiveness and cross-model transferability while exploring defenses for improving robustness.

## Features

- PGD adversarial patch generation
- YOLOv8-based traffic light detection
- BSTLD and LISA dataset support
- Transferability evaluation
- Defense experiments
- Reproducible research pipeline

---

## Repository Structure

```text
configs/          Configuration files
datasets/         Dataset documentation
docs/             Project documentation
experiments/      Research experiments
models/           Model checkpoints
patch_utils/      Shared attack utilities
publication/      Paper, figures, tables
results/          Experimental outputs
scripts/          Training and evaluation scripts
```

---

## Installation

```bash
conda env create -f environment.yml
conda activate traffic-defense
```

---

## Running Experiments

Train a patch

```bash
python scripts/train_patch_yolov8_fixed.py
```

Evaluate

```bash
python scripts/evaluate_patch.py
```

---

## Datasets

- BSTLD
- LISA

See `datasets/README.md` for setup instructions.

---

## Publication

Paper, figures, tables, and poster are located in the `publication/` directory.

---

## License

MIT License
