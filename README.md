# 3D-Vision-ONNX-Models

PyTorch and ONNX workflows for 3D vision models, with support for training, testing, data preparation, and model export.

This repository focuses on 3D point-cloud model pipelines and provides commands for preparing datasets, training models, evaluating checkpoints, and exporting trained models to ONNX format.

## Repository

```bash
git clone --recurse-submodules https://github.com/anchitmulye/3D-Vision-ONNX-Models.git
cd 3D-Vision-ONNX-Models
```

If you already cloned the repository without submodules, initialize them with:

```bash
git submodule update --init --recursive
```


## Project Structure

```text
3D-Vision-ONNX-Models/
├── docs/               # Documents
├── config/             # Global onnx configurations
├── scripts/            # Scripts
├── submodules/         # Forked original repos of SOTA models
└── README.md
```
