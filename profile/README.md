# ALICE-LRI

**ALICE-LRI** is a method for lossless range image generation and reconstruction from spinning 3D LiDAR point clouds. The algorithm automatically estimates all intrinsic sensor parameters from data without requiring calibration files or manufacturer metadata.

This GitHub organization groups together the repositories containing the library implementation, reproducible experiments, and evaluation code for the ALICE-LRI paper.

## 📦 Repositories

### [alice-lri](https://github.com/alice-lri/alice-lri)
C++ and Python library for lossless range image generation and reconstruction from spinning 3D LiDAR point clouds. Automatically estimates all intrinsic sensor parameters from data without calibration files.

[![Release](https://github.com/alice-lri/alice-lri/actions/workflows/release.yml/badge.svg)](https://github.com/alice-lri/alice-lri/actions/workflows/release.yml)
[![Documentation](https://img.shields.io/badge/docs-online-blue.svg)](https://alice-lri.github.io/alice-lri/)
[![PyPI](https://img.shields.io/pypi/v/alice-lri.svg)](https://pypi.org/project/alice-lri/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Features:**
- **Automatic Intrinsic Estimation**: Estimate LiDAR intrinsic parameters from point cloud data. No calibration files or manufacturer metadata needed.
- **Lossless Range Image Projection**: Convert 3D point clouds to 2D range images with zero information loss.
- **Point Cloud Reconstruction**: Unproject range images back to 3D point clouds, recovering original data up to numerical precision.
- **JSON Serialization**: Save and load intrinsic parameters to/from JSON files or strings for easy storage and sharing.
- **Cross-Platform**: Supports Windows, Linux, and macOS.
- **Dual Interface**: Native C++ API and Python bindings for maximum flexibility.

**Documentation:** [alice-lri.github.io/alice-lri](https://alice-lri.github.io/alice-lri/)

---

### [alice-lri-experiments](https://github.com/alice-lri/alice-lri-experiments)
Complete reproducible workflow for ALICE-LRI experiments: code, scripts, and configuration to reproduce all experiments, results, and figures from data preparation to paper outputs across KITTI and DurLAR datasets.


**See:** [REPRODUCIBILITY.md](https://github.com/alice-lri/alice-lri-experiments/blob/main/REPRODUCIBILITY.md) for complete step-by-step instructions.

---

### [rtst-modified](https://github.com/alice-lri/rtst-modified)
**Fork of the Real-Time Spatio-Temporal LiDAR Point Cloud Compression algorithm. Contains both the original implementation and a modified version for evaluation and comparison with ALICE-LRI.**

This repository is used in the experiments to benchmark compression performance when using ALICE-LRI range images versus traditional methods.

**Original Work:** [horizon-research/Real-Time-Spatio-Temporal-LiDAR-Point-Cloud-Compression](https://github.com/horizon-research/Real-Time-Spatio-Temporal-LiDAR-Point-Cloud-Compression)


## 📚 Publications

The ALICE-LRI algorithm and experiments are described in our paper:

> **Title:** _ALICE-LRI: A General Method for Lossless Range Image Generation for Spinning LiDAR Sensors without Calibration Metadata_  
> **Authors:** _Samuel Soutullo, Miguel Yermo, David L. Vilariño, Óscar G. Lorenzo, José C. Cabaleiro, Francisco F. Rivera_  
> **Link:** _TODO: Add link when available_

**How to cite:**
```bibtex
TODO: Add BibTeX citation
```

---

## 🤝 Contributing

We welcome contributions! Whether it's bug reports, feature requests, documentation improvements, or code contributions, please feel free to get involved:

- **Report bugs:** Open an issue in the relevant repository.
- **Suggest features:** Open an issue in the relevant repository.
- **Contribute code:** See [CONTRIBUTING.md](https://github.com/alice-lri/alice-lri/blob/main/CONTRIBUTING.md)

---

## 📄 License

The ALICE-LRI core library is released under the **MIT License**. See individual repositories for specific license information.

---

## 📧 Contact

For questions, collaboration opportunities, or other inquiries, please reach out through email. **See corresponding author of the paper (Samuel Soutullo).**

---
