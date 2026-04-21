# 🌍 AI in Wastewater Treatment

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository hosts machine learning (ML) models, validation datasets, and graphical user interface (GUI) code that demonstrate the applications of **artificial intelligence (AI)** in wastewater treatment.

---

## 📂 Repository Structure

```
AI-in-Wastewater-Treatment/
├── AUTHORS_DECLARATION.md
├── CITATION.cff
├── CONTRIBUTING.md
├── LICENSE
├── Python Environment.yaml
├── README.md
├── .gitignore
│
└── Models and Sample Validation Data/
    ├── Final Effluent Process Parameters/
        └── Sample Data and Folders contaning NN model 
    ├── Lab Parameters/
        └── Sample Data and Folders contaning NN model 
    ├── Plant_1 Inlet Parameters/
        └── Sample Data and Folders contaning NN model 
    ├── Plant_2 Flow Parameter/
        └── Sample Data and Folders contaning NN model 
    ├── Secondary Treatment Parameters/
        └── Sample Data and Folders contaning NN model 
│
└── Model Simulation GUIs code/
```

**Folders**
- `Models and Sample Validation Data/Models/` — Trained models (e.g., Extra Trees, Neural Networks).
- `Models and Sample Validation Data/Sample Datasets/` — Sample inputs for validation/benchmarking.
- `Model Simulation GUIs code/` — GUI code for simulations, contour plots, and operator tools.

---

## ⚡ Key Features
- Predictive modelling for energy and flow/process parameters.
- Advanced ML models with **R² > 0.96** in most scenarios.
- GUI-based simulation & visualisation tools.
- Open license: **CC BY 4.0**.

---

## 🛠️ Getting Started

### 1) Clone
```bash
git clone https://github.com/<your-username>/AI-in-Wastewater-Treatment.git
cd AI-in-Wastewater-Treatment
```

### 2) Environment (example)
- Python ≥ 3.10
- Typical libs: numpy, pandas, scikit-learn, matplotlib, jupyter, streamlit/pyqt (if GUIs are Python-based)
- MATLAB/Octave (if GUIs/models are MATLAB-based)

### 3) Run GUIs
See `Model Simulation GUIs code/` for instructions per GUI.

---

## 📜 License
This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

---

## ✍️ How to Cite
If you use this repository, please cite:

```bibtex
## ✍️ How to Cite
If you use this repository, please cite:

```bibtex
@software{Hassnain_AIWastewater_2026,
  author       = {Muhammad Hassnain and Sarada M.W. Lee and Muhammad Rizwan Azhar and Cameron Veal},
  title        = {AI-ML-in-WastewaterTreatment-GitHubRepo},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.16936040},
  url          = {https://github.com/<your-username>/AI-in-Wastewater-Treatment}
}
```
---

## 🤝 Contributions
Contributions, issues, and pull requests are welcome. Please read `CONTRIBUTING.md` first.

---

## 📨 Contact
Open a GitHub issue for questions or collaboration.

Authors’ Declaration:
---
This repository with associated research paper have been prepared by the authors in their personal capacities based on scientific and technological knowledge and expertise. The views, opinions, interpretations, and conclusions expressed in this work are solely those of the authors and do not reflect the views, positions, or policies of any current or former employers, organisations, governmental bodies, or affiliated institutions. The content was developed independently and without influence from any professional roles or responsibilities held by the authors. Any resemblance to actual events, policies, data, assets, places, or entities is purely coincidental, and no part of this work should be construed as representing or implicating any institution with which any of the authors are, or have been, affiliated.

