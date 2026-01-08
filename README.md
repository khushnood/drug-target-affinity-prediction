# **Molecular Graph Representation Learning: Drug Target Binding Affinity Prediction**

##  **Project Overview**

This repository contains the implementation for the paper **"Molecular graph representation learning: Drug target binding affinity prediction"**, which presents advanced graph neural network architectures for learning molecular representation. The framework leverages state-of-the-art graph representation learning techniques to model molecular structures and predict interaction strengths with high accuracy.

##  **Quick Start**

### **Prerequisites**
- Python 3.8 or higher
- PyTorch 2.1.1+
- torch-geometric==2.4.0

### **Installation**

1. **Clone the Repository:**
```bash
We will put in future after paper acceptance.
git clone https://github.com/khushnood/drug-target-affinity-prediction.git
cd drug-target-affinity-prediction
```



2. **Install Dependencies:**
```bash
pip install torch==2.1.1 

# Install PyTorch Geometric and related packages
pip install torch-scatter torch-sparse torch-cluster torch-spline-conv -f https://data.pyg.org/whl/torch-2.1.0+cu118.html
pip install torch-geometric==2.4.0


# Install other dependencies
pip install tabulate==0.9.0
pip install pandas-flavor
pip install git+https://github.com/bp-kelley/descriptastorus

# Install DeepPurpose (dependency for dataset handling)
pip install git+https://github.com/kexinhuang12345/DeepPurpose.git

# We also acknowledge the code usage of Deeppurpose, descriptastorus....
```

3. **Run the Model:**
```bash
python DTA_Main.py
```
