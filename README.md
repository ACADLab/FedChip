# FedChip: Federated LLM for AI Accelerator Chip Design

Welcome to the official repository for **FedChip**, a federated fine-tuning framework designed to enable collaborative, privacy-preserving large language model (LLM) training for automated hardware design.

> **Paper**: [FedChip: Federated LLM for Artificial Intelligence Accelerator Chip Design](https://iclad.ai/accepted-papers)
> **Authors**: Mahmoud Nazzal, Khoa Nguyen, Deepak Vungarala, Ramtin Zand, Shaahin Angizi, Hai Phan, Abdallah Khreishah
> **Conference**: ICLAD 2025

---

## 🔍 Overview

LLMs hold great promise for automating hardware design, but domain-specific training data is often siloed due to privacy and IP concerns. **FedChip** addresses this by applying **federated learning (FL)** to fine-tune LLMs across multiple parties without sharing raw data.

FedChip is evaluated using:
- Our custom dataset **APTPU-Gen** (30,000+ Verilog design samples with power, performance, and area metrics)
- A novel evaluation metric: **Chip@k**, to assess multi-objective design quality
- Federated fine-tuning using **LoRA** for efficient local updates

---

## 📊 Dataset: APTPU-Gen

**APTPU-Gen** is a large-scale dataset derived from the Approximate Tensor Processing Unit (APTPU) architecture.

- 📈 **30,000+ designs** across varied configurations (e.g., array size, data width, approximation mode)
- ⚙️ Each design includes:
- Verilog HDL
- A natural language description
- PPA metrics: Power, Performance (Slack), Area
- 📚 Citation
If you use FedChip or APTPU-Gen in your work, please cite:
```bash
@inproceedings{nazzal2025fedchip,
title={FedChip: Federated LLM for Artificial Intelligence Accelerator Chip Design},
author={Nazzal, Mahmoud and Nguyen, Khoa and Vungarala, Deepak and Zand, Ramtin and Angizi, Shaahin and Phan, Hai and Khreishah, Abdallah},
booktitle={Proceedings of the International Conference on Learning for Automated Design (ICLAD)},
year={2025}
}
```

🔐 License
MIT License


✨ Acknowledgements
This work was supported by the New Jersey Institute of Technology and the University of South Carolina. We thank the OpenROAD and OpenFedLLM communities.


📬 Contact
For questions, feel free to open an issue or contact:
📧 ```mn69@njit.edu, dv336@njit.edu, nk569@njit.edu```

