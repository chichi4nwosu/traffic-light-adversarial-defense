# Traffic Light Adversarial Defense
<p align="center">
  <img src="publication/figures/poster_preview.png" width="900">
</p>
> Research on adversarial patch attacks and defense strategies for YOLOv8 traffic light detection using the BSTLD and LISA datasets.

---

## Overview

This repository contains the implementation and experimental results for research on adversarial attacks against traffic light detection systems. The project evaluates the robustness of YOLOv8 under adversarial patch attacks and investigates defense strategies through adversarial training.

This work was completed as part of a Research Experience for Undergraduates (REU) program.

---
![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0-red)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-green)
![Research](https://img.shields.io/badge/Research-REU-orange)

## Experimental Pipeline
BSTLD / LISA
        │
        ▼
Baseline YOLOv8
        │
        ▼
Generate Universal Patch
        │
        ▼
Attack Evaluation
        │
        ▼
Adversarial Training
        │
        ▼
Defense Evaluation

## Features

- YOLOv8 traffic light detection
- Universal adversarial patch attacks
- Expectation over Transformation (EOT)
- Adversarial training defense
- BSTLD experiments
- LISA experiments
- Transferability evaluation

---

## Repository Structure

```
configs/         Configuration files
datasets/        Dataset documentation
docs/            Experiment notes
experiments/     Attack and defense experiments
models/          Trained model checkpoints
publication/     Poster and publication materials
results/         Figures and evaluation results
scripts/         Training and evaluation scripts
```

---

## Datasets

- Bosch Small Traffic Lights Dataset (BSTLD)
- LISA Traffic Light Dataset

---

## Current Status

### Completed

- Baseline YOLOv8 training
- Universal adversarial patch attack
- Adversarial training defense
- Evaluation on BSTLD
- Evaluation on LISA

### Future Work

- Digital PGD attack baseline
- Cross-model transferability matrix
- Statistical evaluation across multiple random seeds
- Research paper submission

---

## Citation

Coming soon.
