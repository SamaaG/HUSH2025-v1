# Reproducibility Code for HUSH

This repository contains all the necessary code, datasets, and instructions to reproduce the experiments presented in the **HUSH** paper, submitted to VLDB2025. HUSH is a framework designed to enhance machine unlearning efficiency by leveraging shared layers in sharding-based approaches. The repository is structured to enable reproducibility for researchers and practitioners.

---

## Contents
- **Experiment Scripts**: Code for running all experiments discussed in the paper, including accuracy, retraining latency, and information leakage analyses.
- **Pre-trained Models**: Checkpoints for shared trunk and branch models used in the experiments.
- **Datasets**: Scripts for downloading and preparing datasets, including CIFAR-10, MNIST, Fashion-MNIST, and SVHN.
- **Evaluation Metrics**: Tools to measure accuracy, retraining latency, and privacy leakage metrics.
- **HUSH-DP Implementation**: Integration of differential privacy guarantees within HUSH, including customizable privacy budgets.
- **Ablation Studies**: Code for reproducing ablation studies on trunk ratios.

---
## Citation
If you use this repository, please cite the HUSH paper.

---

## Acknowledgments
This repository is provided as part of the reproducibility requirements for VLDB2025. For any issues or questions, please feel free to open an issue or contact us.
