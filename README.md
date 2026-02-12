# CSGNN

Correlation-guided Subgraph Graph Neural Network (CSGNN)  
for Essential Protein Identification

---

## Overview

This repository is associated with the manuscript:

> **A CSGNN model-based method for essential protein identification**

CSGNN is a correlation-guided graph neural network framework designed for node-level essential protein prediction.  
The model integrates:

- Activity-filtered time-series gene expression
- Correlation-guided subgraph construction
- Multi-order graph convolution
- Attention-based neighborhood reweighting
- Interaction-aware contextual aggregation

By modeling functional consistency within correlation-guided subgraphs, CSGNN learns biologically informed multi-scale protein representations for essentiality inference.

---

## Current Status

The manuscript is currently **under peer review**.

To ensure compliance with journal policies, the full implementation code and processed datasets will be released after the review process is completed.

We appreciate your patience and interest.

---

## Data Sources

The experiments are conducted on:

- *Saccharomyces cerevisiae* (yeast)
- *Escherichia coli*

Public databases used include:

- DIP (Protein–Protein Interaction data)
- GEO (Gene Expression data)
- MIPS / SGD / DEG / SGDP (Essential protein annotations)

Detailed preprocessing procedures will be provided upon release.

---

## Planned Release

After the manuscript is accepted:

- Full training and evaluation code
- Processed datasets
- Reproducibility instructions
- Hyperparameter configurations

will be made publicly available in this repository.

---

## Contact

For questions regarding the manuscript or early collaboration inquiries, please contact:

[Your Name / Email]

---

Thank you for your interest in CSGNN.

