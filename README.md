# Trashly – Real-time Waste Classification with Deep Learning

Trashly is an end-to-end computer vision project for waste image classification. It covers dataset generation, image preprocessing (including background removal), CNN training and evaluation, and ONNX export for efficient inference.

> **Status:** Ongoing / research prototype.

---

## Overview

The goal of Trashly is to build a reproducible pipeline that classifies waste images into different categories and can be deployed for real-time inference. The repository is organized as a sequence of notebooks, from data preparation to model export and testing.

**Main pipeline:**

1. Generate or collect the waste image dataset.
2. Preprocess images (including background removal experiments).
3. Train a CNN classifier.
4. Evaluate model performance.
5. Export the trained model to ONNX.
6. Run inference tests with the exported model.

---

## Features

- End-to-end waste image classification pipeline
- Dataset generation and preprocessing notebooks
- Background removal preprocessing example
- CNN training and evaluation
- ONNX model export for efficient inference
- Modular notebooks for experimentation and reproducibility

---

## Tech Stack

- Python
- PyTorch / torchvision
- OpenCV
- NumPy
- scikit-learn
- ONNX / ONNX Runtime
- Jupyter Notebook

---

## Repository Structure

```text
Trashly/
├── modelos/                              # Saved models / exported models
├── Clasificación_basura_procesado_datos.ipynb
├── Entrenamiento.ipynb
├── Generar_dataset.ipynb
├── Prueba modelo onnx.ipynb
├── Ejemplo_eliminar_fondo.ipynb
└── README.md
