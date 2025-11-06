# Machine Learning Project 2

## About
This project implements a **Multilayer Perceptron (MLP)** model using Python to perform supervised learning and generate predictions for the dataset.
It includes full preprocessing, model training, evaluation, and export of prediction results.

## Features
- Data preprocessing (cleaning, encoding, and scaling)
- Neural network model implementation using scikit-learn or PyTorch
- Evaluation metrics: accuracy, loss, and validation performance
- Export of predictions to CSV for submission or further analysis

## Repository Structure
```
.
├── Group_26_Project2.ipynb            # Jupyter notebook with full code
├── project_adult.csv                  # Training dataset (not included here)
├── project_validation_inputs.csv      # Validation dataset (not included here)
├── Group_26_MLP_PredictedOutputs.csv  # Predicted output file
└── README.md                          # Project documentation
```

## Installation

Clone the repository:  
```bash
git clone https://github.com/jbarnes04/MachineLearningProject2.git
cd MachineLearningProject2
```

Install dependencies:  
```bash
pip install -r requirements.txt
```

**Requirements:**  
- Python 3.8+  
- NumPy  
- Pandas  
- Matplotlib  
- scikit-learn  

---

## Usage

1. Open the Jupyter notebook:  
   ```bash
   jupyter notebook Group_26_Project2.ipynb
   ```

2. Run all cells to:  
   - Preprocess the dataset  
   - Train and evaluate the MLP models  
   - Export predicted outputs to `Group_26_MLP_PredictedOutputs.csv`

---

## Results  
- The trained MLP model achieved consistent performance across training and validation datasets.
- Predicted outputs are available in the included CSV file for further comparison and analysis.

---

## Authors  
**Group 26**
– Jodi Barnes & Lauren Moffett  
