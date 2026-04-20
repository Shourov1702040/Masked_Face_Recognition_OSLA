# OSLA: Masked Face Recognition

This repository contains the implementation of the **Oracle–Shadow Learning Architecture (OSLA)**, a deep learning framework for **masked face recognition**.

OSLA uses a dual-stream design:
- **Oracle network** (trained on unmasked faces) as a stable identity reference  
- **Shadow network** (trained on masked faces)  
- A latent-space alignment strategy to preserve identity under occlusion  

---

## 📁 Contents

- `OSLA_notebook.ipynb` – Main implementation (training + evaluation)

---

## 📊 Dataset

The model is trained and evaluated on the **HSTU Masked Face Dataset (HMFD)**:
- Real masked and unmasked images (no synthetic masks)
- 264 identities, 20 samples each
- Includes pose and mask variations

The dataset is linked inside the notebook and can be accessed via **Google Drive**.

