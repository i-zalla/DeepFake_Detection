# Multimodal Lip-Sync Deepfake Detection 

This repository contains our deepfake detection project, where we worked on detecting **lip-sync manipulation** using a **multimodal approach** (audio + video). The goal of this work is to detect inconsistencies between spoken audio and lip movements.

### What the project includes

- **Feature extraction pipeline**
  - Audio features extracted using **XLS-R** (wav2vec 2.0 based model).
  - Visual features extracted from video frames using **ViT-B/16** (Vision Transformer).
- **Classification model**
  - A **modified MS-TCN** (Multi-Stage Temporal Convolutional Network) is used for temporal classification.
  - Input to the model is a sequence of fused audio-visual embeddings.
  - Output is a binary prediction: **real vs. lip-sync deepfake**.

### Dataset

This project uses an **extended version of the PolyglotFake dataset**, which includes multilingual lip-sync deepfake samples. 
### Objective

The goal was to experiment with:
- Multimodal learning
- Temporal modeling for deepfake detection
- Cross-modal feature fusion
- Deepfake detection robustness across languages


### Notes

- This project is purely **research and educational**.
- The code is shared for **transparency and academic reference**.
- It may require adjustments to run depending on environment and dataset paths.

---


