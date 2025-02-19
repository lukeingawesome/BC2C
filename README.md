# BC2C

**Official code for the paper**  
**“Bringing CLIP to the Clinic: Dynamic Soft Labels and Negation-Aware Learning for Medical Analysis”**

---

## Table of Contents
- [Abstract](#abstract)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [CXR-Align Benchmark](#cxr-align-benchmark)
- [Model Checkpoints](#model-checkpoints)
- [Citation](#citation)

---

## Abstract
The development of large-scale image-text pair datasets has significantly advanced self-supervised learning in Vision-Language Processing (VLP). However, directly applying general-domain architectures such as CLIP to medical data presents unique challenges, particularly in handling negations and addressing the inherent data imbalance of medical datasets.

In this work, we propose a novel approach that integrates clinically enhanced dynamic soft labels and medical graphical alignment to improve clinical comprehension and optimize the applicability of contrastive loss in medical contexts. Furthermore, we introduce negation-based hard negatives to deepen the model’s understanding of the complexities of clinical language. Our approach integrates seamlessly into any medical CLIP training pipeline and achieves state-of-the-art performance across multiple tasks, including zero-shot classification, fine-tuned classification, and report retrieval.

To assess our model’s capacity for clinical language comprehension, we introduce **CXR-Align**, a benchmark specifically designed to evaluate negation and clinical information understanding within chest X-ray (CXR) datasets. Experimental results demonstrate that our proposed methods are straightforward to implement and generalize effectively across contrastive learning frameworks, thereby enhancing medical VLP capabilities and advancing clinical language understanding in medical imaging.

---

## Features
- **CXR-Align Benchmark**: A specialized benchmark for evaluating negation and clinical concepts in CXR datasets.
- **BC2C model weights**: Pretrained weights available (see [Model Checkpoints](#model-checkpoints) below).

---

## Requirements
- Python 3.7+ (tested on Python 3.10)
- PyTorch (version >= 1.10)
- CUDA-compatible GPU (recommended for training)
- Other dependencies (see `requirements.txt`)

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lukeingawesome/BC2C.git
   cd BC2C
2. **(Recommended) Create and activate a conda environment:**
   ```bash
   conda create -n clip python=3.10
   conda activate clip
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt

## CXR-Align Benchmark
Coming soon on physionet.

## Model Checkpoints
The model weights can be downloaded from:
- [Download weights](https://drive.google.com/file/d/1aOEwx8i_b_mrIlei0lOuTJTZia4HgFM-/view?usp=sharing)  - (N-TC)
- (N-TCG coming soon)


## Citation

If you use our work, please cite:

```
@inproceedings{BC2C,
  title={Bringing CLIP to the Clinic: Dynamic Soft Labels and Negation-Aware Learning for Medical Analysis},
  author={...},
  booktitle={...},
  year={2023}
}


