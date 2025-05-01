# Quantum Sentinel 🛡️

**Quantum Sentinel** is a cutting-edge hybrid fraud detection system that integrates classical machine learning with quantum machine learning to enhance accuracy, speed, and security in fraud prediction tasks. Built on the popular Kaggle Credit Card Fraud Detection dataset, this project showcases the power of quantum-assisted anomaly detection — deployed via an interactive Streamlit dashboard for seamless visualization and comparison.

---

## 🚀 Features

- **Hybrid Fraud Detection System**: Combines classical SVM and Quantum SVM models.
- **Quantum Machine Learning**: Utilizes PennyLane for quantum circuit design and quantum kernel methods.
- **Streamlit Dashboard**: User-friendly interface to visualize model predictions, performance metrics, and comparisons.
- **Performance Benchmarking**: Compare accuracy, execution time, and ROC curves of Quantum vs Classical models.
- **Customizable Pipeline**: Easily extendable for other datasets and fraud detection scenarios.

---

## 🛠️ Technologies Used

- Python 3.x
- PennyLane (Quantum Machine Learning)
- Scikit-learn (Classical ML)
- Streamlit (Dashboard)
- Pandas, NumPy, Matplotlib, Seaborn (EDA & Visualization)

---

## 📊 Model Overview

| Model Type | Framework | Key Technique |
|------------|-----------|---------------|
| Classical SVM | Scikit-learn | RBF Kernel |
| Quantum SVM | PennyLane + Cirq Backend | Quantum Kernel Methods |

---

## 📂 Project Structure

```
Quantum-Sentinel/
├── data/                # Dataset (Credit Card Fraud Detection)
├── notebooks/           # EDA & Model Training Notebooks
├── app/                 # Streamlit Dashboard Code
├── models/              # Saved Models & Parameters
├── utils/               # Helper Functions
├── requirements.txt     # Project Dependencies
└── README.md
```

---

## ⚡ Quickstart

```bash
# Clone the repo
git clone https://github.com/silverballz/Quantum-Sentinel.git
cd Quantum-Sentinel

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit dashboard
streamlit run app/dashboard.py
```

---

## ✨ Project Highlights

- **Quantum Kernel Visualization**: Explore how quantum feature encoding maps classical data into higher-dimensional Hilbert spaces.
- **ROC Curve Comparison**: Understand the performance trade-off between classical and quantum models visually.
- **End-to-End Workflow**: From data preprocessing, feature selection, and model training to dashboard deployment.

---

## 👨‍💻 Contributors

- **Anurag Sharma** — [LinkedIn](https://www.linkedin.com/in/anurag-sharma-362664240/) | [GitHub](https://github.com/silverballz)
- **Nityansh Pant** — Collaborator & Co-Developer

---

## 📢 Future Work

- Integrate more quantum algorithms (VQC, Quantum Neural Networks)
- Optimize quantum circuit parameters for faster execution
- Expand to other anomaly detection domains (Healthcare, Cybersecurity)
- Publish research paper based on project results

---

## 📜 License

This project is licensed under the MIT License — see the `LICENSE` file for details.

---

## 🌐 Acknowledgements

- Kaggle Credit Card Fraud Detection Dataset
- PennyLane & Cirq Documentation
- Streamlit Community

