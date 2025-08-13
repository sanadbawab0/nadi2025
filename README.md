# Spoken Arabic Dialect Identification (ADI) – SHAREED Task @ ArabicNLP 2025

This repository implements a **speech classification pipeline** fusing **ECAPA-TDNN** and **WavLM** for **Spoken Arabic Dialect Identification (ADI)**. Developed for the **Shared Task, ArabicNLP 2025 (NADI)**.  

**Paper:** *Lahjati: A ECAPA-WavLM Fusion with Multi-Stage Optimization*  

**Authors & Affiliations:**  
- **Sanad Albawwab**  
  Decision Support & Automation - Applied AI Division  
  Royal Scientific Society, Amman, Jordan  
  sanad.bawwab@rss.jo  

- **Omar Qawasmeh**  
  Data Science Department  
  Princess Sumaya University for Technology, Amman, Jordan  
  o.alqawasmeh@psut.edu.jo  

---

## Features

- **Model**: ECAPA-TDNN + WavLM embeddings, fused with projection layers and classifier.  
- **Training**: Gradual unfreezing, phased LR scheduler, gradient clipping.  
- **Evaluation**: Accuracy, average NIST SRE cost, FPR, FNR.  

---


