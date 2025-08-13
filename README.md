# Spoken Arabic Dialect Identification (ADI) – HAREED Task @ ArabicNLP 2025

This repository implements a **speech classification pipeline** fusing **ECAPA-TDNN** and **WavLM** for **Spoken Arabic Dialect Identification (ADI)**. Developed for the **SHAREED Task, ArabicNLP 2025 (NADI)**.

---

## Features

- **Model**: ECAPA-TDNN + WavLM embeddings, fused with projection layers and classifier.  
- **Training**: Gradual unfreezing, phased LR scheduler, gradient clipping.  
- **Evaluation**: Accuracy, average NIST SRE cost, FPR, FNR.  

