# SGFN: A Spectral Graph Fusion Network for Spatial Transcriptomics Analysis

![image](model.png)

SGFN is a deep learning framework for spatial transcriptomics analysis. It integrates gene expression profiles, spatial neighborhood information, and graph spectral features to identify spatial domains from spatial transcriptomics data.

This repository provides the source code and Jupyter notebooks for reproducing the running process of SGFN on spatial transcriptomics datasets.

---

## Getting Started

* [Requirements](#requirements)
* [Installation](#installation)
* [Tutorials](#tutorials)
* [Repository Structure](#repository-structure)
* [Contact](#contact)

---

## Tutorials

We provide Jupyter notebooks to demonstrate the running process of SGFN.

* [Human Breast Cancer](Human_Breast_Cancer.ipynb)
* [Human Brain Metastasis](humanbrain_metastasis.ipynb)

The notebooks include data loading, preprocessing, SGFN model training, spatial domain identification, and visualization.

---

## Requirements

To install and run `SGFN`, we recommend using Python 3.9.

Main dependencies:

```text
python == 3.9
torch == 1.12.1
scanpy == 1.9.8
anndata == 0.10.5.post1
numpy == 1.26.4
pandas
scipy
scikit-learn == 1.4.1.post1
matplotlib == 3.8.3
seaborn
tqdm == 4.67.1
networkx
jupyter
ipykernel
