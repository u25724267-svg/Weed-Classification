# 📘 Project README

## Overview
This repository contains the code and resources for training and evaluating deep learning models using TensorFlow/Keras. The provided Jupyter Notebook (`main.ipynb`) demonstrates a full workflow, including data preprocessing, model definition, training, and evaluation.  

The project is structured to support reproducibility, modular experimentation, and easy integration with new datasets or architectures.

---

## 🚀 Features
- Automated **data preprocessing** pipeline (train/test split, augmentations, normalization).  
- **Configurable model builder** for CNN architectures with adjustable hyperparameters.  
- **Training pipeline** with checkpointing and early stopping.  
- **Evaluation suite** for accuracy, precision/recall, F1-score, and ROC-AUC metrics.  
- Support for **experiment sweeps** with different activation functions and optimizers.  

---

## 📂 Repository Structure
```
├── main.ipynb        # Core notebook: training + evaluation pipeline
├── data/             # Place your dataset or ZIP file here
├── models/           # Saved model checkpoints
├── results/          # Training history and evaluation outputs
└── README.md         # Project documentation
```

---

## ⚙️ Requirements
- Python 3.9+  
- TensorFlow 2.20+  
- NumPy  
- Pandas  
- Matplotlib  
- scikit-learn  

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 📊 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```
2. Add your dataset (`.zip`) to the `data/` folder.  
3. Open the notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
4. Run all cells to preprocess data, train the model, and evaluate performance.  

---

## 🧪 Customization
- Modify the `Config` class in the notebook to adjust:
  - Image size  
  - Batch size  
  - Augmentation strategy  
  - Optimizer, activation functions, and number of epochs  

- Extend the sweep runner script (`sweep_runner.py`) to perform hyperparameter tuning.  

---

## 📈 Results
After training, the notebook outputs:
- Training/validation accuracy and loss curves  
- Classification metrics (precision, recall, F1-score)  
- Confusion matrix  
- ROC curves  

These are saved to the `results/` folder for later reference.  

---

## 🤝 Contributing
Contributions are welcome! Please fork the repo, create a feature branch, and submit a pull request.  

---

## 📜 License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.  
