# GABA Analogues – RDKit Cheminformatics Project

This repository contains a Jupyter Notebook (`GABA_analysis.ipynb`) dedicated to the cheminformatics analysis of **GABA (γ-aminobutyric acid) analogues**.  
The goal of the project is to explore structure–property relationships, generate descriptors, visualize molecules, and prepare the foundation for future in silico work such as conformer generation or docking.

This project helps to integrate computational chemistry tools (RDKit, Pandas, NumPy) into practical synthetic chemistry workflows.

---

## 🔬 Features

### ✔ **1. SMILES processing**
- Conversion of SMILES into RDKit molecular objects  
- Support for stereochemistry  
- Basic structure validation  

### ✔ **2. Molecular descriptor calculation**
The notebook currently calculates:
- **LogP (MolLogP)**
- **Topological Polar Surface Area (TPSA)**
- **Molecular Weight (MolWt)**

These descriptors are relevant for:
- membrane permeability,
- CNS penetration,
- lipophilicity balance,
- comparison with known GABA analog drugs (pregabalin, gabapentin etc.)

### ✔ **3. Visualization**
- 2D molecular drawings  
- Rendering inside Jupyter Notebook  
- Side-by-side comparison of molecules  

### ✔ **4. Data handling**
Uses Pandas to:
- load CSV libraries of GABA analogs
- filter them by properties (e.g., `LogP < 1`)
- prepare datasets for further analysis

---

## 📘 Future directions

The project is planned to grow with further cheminformatics functionality:
- 3D conformer generation  
- similarity fingerprints (Morgan, MACCS)  
- clustering of analogues  
- basic receptor docking (with external tools)  
- HOMO/LUMO approximation using semi-empirical methods (xTB)  

This roadmap allows combining synthetic chemistry with computational insights.

---

## 📁 How to use

1. Clone or download the repository:
2. git clone https://github.com/vkozelchem-spec/GABA-analogs-RDKit
3. 2. Open `GABA_analysis.ipynb` in:
- **JupyterLab**, or  
- **Google Colab** (click the badge below)

3. Install dependencies if running locally:
- Python 3.10+
- RDKit  
- pandas  
- numpy  

4. Run the notebook cells sequentially.

---

## 🚀 Open in Google Colab

Click the badge to launch the notebook directly:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/vkozelchem-spec/GABA-analogs-RDKit/blob/main/GABA_analysis.ipynb
)

---

## 👤 Author

**Volodymyr Kozel**  
Synthetic Organic Chemist  
Germany  
Experience in academia and industry  
Developing skills in cheminformatics (RDKit, Pandas)

---

## 📄 License

MIT License – free to use and modify.

