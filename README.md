# BC2C

**Official code for the paper**  
**“Bringing CLIP to the Clinic: Dynamic Soft Labels and Negation-Aware Learning for Medical Analysis”**

---

## Table of Contents
- [Abstract](#abstract)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [CXR-Align Benchmark](#cxr-align-benchmark)
- [Model Checkpoints](#model-checkpoints)
- [Citation](#citation)
- [License](#license)

---

## Abstract
The development of large-scale image-text pair datasets has significantly advanced self-supervised learning in Vision-Language Processing (VLP). However, directly applying general-domain architectures such as CLIP to medical data presents unique challenges, particularly in handling negations and addressing the inherent data imbalance of medical datasets.

In this work, we propose a novel approach that integrates clinically enhanced dynamic soft labels and medical graphical alignment to improve clinical comprehension and optimize the applicability of contrastive loss in medical contexts. Furthermore, we introduce negation-based hard negatives to deepen the model’s understanding of the complexities of clinical language. Our approach integrates seamlessly into any medical CLIP training pipeline and achieves state-of-the-art performance across multiple tasks, including zero-shot classification, fine-tuned classification, and report retrieval.

To assess our model’s capacity for clinical language comprehension, we introduce **CXR-Align**, a benchmark specifically designed to evaluate negation and clinical information understanding within chest X-ray (CXR) datasets. Experimental results demonstrate that our proposed methods are straightforward to implement and generalize effectively across contrastive learning frameworks, thereby enhancing medical VLP capabilities and advancing clinical language understanding in medical imaging.

---

## Features
- **CXR-Align Benchmark**: A specialized benchmark for evaluating negation and clinical concepts in CXR datasets.

---

## Requirements
- Python 3.7+  
- PyTorch (version >= 1.10)  
- CUDA-compatible GPU (recommended for training)  
- Other dependencies (to be added upon release)

A detailed `requirements.txt` or environment file will be provided soon.

---

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/lukeingawesome/BC2C.git
   cd BC2C
