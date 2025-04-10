# **Pennylane-ImageSegmentation: Qubit-Efficient Variational Quantum Algorithms for Image Segmentation**

[![Paper DOI](https://img.shields.io/badge/DOI-10.1109/QCE60285.2024.00059-orange)](https://doi.org/10.1109/QCE60285.2024.00059)  
[![arXiv](https://img.shields.io/badge/arXiv-2405.14405-green)](https://doi.org/10.48550/arXiv.2405.14405)  
[![Conference](https://img.shields.io/badge/Conference-QCE'24-blue)](https://qce.quantum.ieee.org/2024/)  
[![License: LGPL v2.1](https://img.shields.io/badge/License-LGPL%20v2.1-blue.svg)](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)  
[![LinkedIn: SupreethMV](https://img.shields.io/badge/LinkedIn-Supreeth%20Mysore%20Venkatesh-blue)](https://www.linkedin.com/in/supreethmv/)  
[![Website: SupreethMV](https://img.shields.io/badge/Website-www.supreethmv.com-brightgreen)](https://www.supreethmv.com)

<figure>
  <img src="_repo_data/vqa-segmentation.png" alt="VQA Segmentation Overview" width="600">
  <figcaption>
    Architecture for segmenting an image by transforming it into a graph and solving the corresponding minimum cut as a QUBO problem using variational quantum circuits
  </figcaption>
</figure>

---

## **Overview**

Welcome to **NISQ-Seg**, the official repository for the paper **"Qubit-efficient Variational Quantum Algorithms for Image Segmentation"**, accepted at the Quantum Computing and Engineering 2024 (QCE'24) conference by IEEE. This repository provides the full pipeline for reproducing the experimental results and demonstrations of the three primary encoding methods introduced in the paper:

<figure>
  <img src="_repo_data/pipeline_overview.png" alt="VQA Segmentation Overview" width="600">
  <figcaption>
    Image is converted to an undirected weighted graph with similarity of the pixels as the edge weight metric, then solving the minimum cut obtains the segmentation of the image.</a>
  </figcaption>
</figure>


1. **Parametric Gate Encoding (PGE)**
2. **Ancilla Basis Encoding (ABE)**
3. **Adaptive Cost Encoding (ACE)**


These quantum techniques are optimized for **Noisy Intermediate-Scale Quantum (NISQ)** devices and demonstrate efficient qubit usage for **graph-based image segmentation** tasks.

### **Paper Preprint**
The preprint is available on [arXiv](https://doi.org/10.48550/arXiv.2405.14405).

### **Link to Official repo in Qiskit**
The official repository is implemented in Qiskit [GitHub](https://github.com/supreethmv/NISQ-Seg)

---

Explore the different encoding methods by running the provided Jupyter notebooks:

- `tutorial.ipynb`: A walkthrough of the image segmentation pipeline for a 4x4 image.

---

## **Citing this Work**

If you find this code useful in your research, please cite the following paper:

```bibtex
@INPROCEEDINGS{10821431,
  author={Venkatesh, Supreeth Mysore and Macaluso, Antonio and Nuske, Marlon and Klusch, Matthias and Dengel, Andreas},
  booktitle={2024 IEEE International Conference on Quantum Computing and Engineering (QCE)}, 
  title={Qubit-Efficient Variational Quantum Algorithms for Image Segmentation}, 
  year={2024},
  volume={01},
  pages={450-456},
  doi={10.1109/QCE60285.2024.00059}
  }
```

---

## **Contact**

**Supreeth Mysore Venkatesh**  

For any inquiries, please reach out to:

- Email: contact@supreethmv.com  
- LinkedIn: [Supreeth Mysore Venkatesh](https://www.linkedin.com/in/supreethmv/)  
- Website: [www.supreethmv.com](https://www.supreethmv.com)


## Contributors

[![Supreeth Mysore Venkatesh](_repo_data/supreethmv.jpg)](https://www.supreethmv.com)