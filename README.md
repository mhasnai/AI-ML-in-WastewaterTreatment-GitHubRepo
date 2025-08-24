# 🌍 AI in Wastewater Treatment

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository hosts machine learning (ML) models, validation datasets, and graphical user interface (GUI) code that demonstrate the applications of **artificial intelligence (AI)** in wastewater treatment.

> ## Abstract
> In the fight against climate change, population growth, and urbanisation, the integration of machine learning (ML) is redefining how wastewater management is conducted in a more efficient, robust, and environmentally friendly manner. This paper explores the powerful applications of ML, a subset of artificial intelligence (AI), in a wastewater treatment plant. It focuses on key areas, including predicting and modelling inlet wastewater flow, inlet band screen levels, aeration energy, aeration flow rate, final effluent pump station energy, ocean discharge pressure, and critical effluent quality parameters such as final effluent ammonium, mixed liquor suspended solids, and final effluent suspended solids. Historical data are extracted from instruments and laboratory tests at variable frequencies. Two advanced ML and AI models, extra trees (ExT) and neural networks (NN), are examined for their predictive accuracy. While the predictions for effluent quality were satisfactory, the models demonstrated remarkable performance, with a coefficient of determination (R²) for validation and prediction values exceeding 0.96 in most scenarios. Additionally, simulation graphical user interfaces have been developed for each application, and NN with contour plots are utilised to assess combinations for setting boundary conditions, ensuring safe and efficient operations. This work demonstrates how ML can address specific industrial operational challenges, reduce energy consumption, and promote safer and more sustainable wastewater treatment, representing a significant step in addressing global water issues.

---

## 📂 Repository Structure

```
AI-in-Wastewater-Treatment/
├── LICENSE
├── README.md
├── .gitignore
├── CONTRIBUTING.md
├── CITATION.cff
│
├── Models and Sample Validation Data/
│   ├── Models/
│   └── Sample Datasets/
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

```
@misc{AI_in_Wastewater_Treatment,
  title  = {AI in Wastewater Treatment},
  author = {<Your Name>},
  year   = {2025},
  url    = {https://github.com/<your-username>/AI-in-Wastewater-Treatment},
  note   = {Code, models, and datasets accompanying the wastewater ML study.}
}
```
Authors’ Declaration
This repository with associated research paper have been prepared by the authors in their personal capacities based on scientific and technological knowledge and expertise. The views, opinions, interpretations, and conclusions expressed in this work are solely those of the authors and do not reflect the views, positions, or policies of any current or former employers, organisations, governmental bodies, or affiliated institutions. The content was developed independently and without influence from any professional roles or responsibilities held by the authors. Any resemblance to actual events, policies, data, assets, places, or entities is purely coincidental, and no part of this work should be construed as representing or implicating any institution with which any of the authors are, or have been, affiliated.
---

## 🤝 Contributions
Contributions, issues, and pull requests are welcome. Please read `CONTRIBUTING.md` first.

---

## 📨 Contact
Open a GitHub issue for questions or collaboration.
