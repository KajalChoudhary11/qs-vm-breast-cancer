# 🧠 Quantum Kernel Methods for Breast Cancer Classification

This project demonstrates how to use **Quantum Support Vector Machines (QSVM)** with **Qiskit** to classify breast cancer tumors as malignant or benign using only 4 normalized features.

---

## 📌 About the Project

With the rise of Noisy Intermediate-Scale Quantum (NISQ) devices, hybrid quantum-classical ML algorithms like QSVM are gaining importance. This project benchmarks **quantum kernels** against classical classifiers on the Breast Cancer dataset using Qiskit.

---

## 🧪 Technologies Used

- Python 3.10+
- Qiskit Machine Learning
- Scikit-learn
- NumPy, Matplotlib
- Jupyter Notebook
- IBM Quantum (for simulation/transpilation)

---

## 📁 Project Structure

'''├── QSVM_BreastCancer.ipynb # Main notebook
├── report.tex # LaTeX report
├── report.pdf # Compiled report
├── requirements.txt # Dependencies (optional)
├── LICENSE # License (MIT, etc.)
└── .gitattributes # Line ending normalization
'''

---

## 🧠 Quantum Methods Used

- `ZZFeatureMap` with 2 repetitions
- `PauliFeatureMap` with Pauli gates {X, Y, Z}
- `FidelityQuantumKernel` from Qiskit
- Transpilation for circuit depth, gate count, and width

---

## 📊 Accuracy Summary

| Model | Accuracy |
|-------|----------|
| QSVM (PauliFeatureMap) | 96.4% |
| QSVM (ZZFeatureMap) | 92.8% |
| SVM (RBF kernel) | 96.4% |
| Random Forest | 95.3% |

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🤝 Acknowledgements

- Guided by **Prof. Shiva Pokhrel**, Deakin University
- Part of **FTP 8.0 – Advanced Quantum Computing Track**
- Inspired by IBM Qiskit tutorials and research

---

## ✨ Contact

📧 kajal.choudhary@kgpian.iitkgp.ac.in  
📍 Department of Physics, IIT Kharagpur
