# Lung Health Classification Project 🩺📊

A Python-based project using PyTorch for image classification to determine whether lungs are healthy or infected based on X-ray images. The dataset was sourced from Google, and the analysis and model training were performed in Jupyter Notebook.

---

## ✨ Features

- **Dataset Handling**: X-ray images were preprocessed and split into training, validation, and test sets.
- **Model Architecture**: Built and trained a deep learning model using PyTorch.
- **Evaluation**: Assessed model performance using metrics like accuracy and loss.
- **Visualization**: Plotted results and confusion matrices for insights.
- **Deployment Readiness**: Prepared the model for integration into larger healthcare systems.

---

## 🛠️ Requirements

- Python 3.7+
- Jupyter Notebook
- PyTorch
- NumPy
- Matplotlib
- Pandas
- scikit-learn

Install dependencies:
```bash
pip install torch torchvision numpy matplotlib pandas scikit-learn
```

---

## 🚀 Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/lung-health-classification.git
   cd lung-health-classification
   ```

2. **Open the Jupyter Notebook**
   ```bash
   jupyter notebook Lung_Classification.ipynb
   ```

3. **Run the Notebook**
   - Follow the step-by-step cells in the notebook to preprocess data, train the model, and evaluate its performance.

4. **Customize for Your Needs**
   - Replace the dataset path with your own X-ray images if needed.

---

## 📁 File Descriptions

- `Lung_Classification.ipynb`: Jupyter Notebook containing the entire workflow, including preprocessing, model training, and evaluation.
- `data/`: Directory containing X-ray images used for the project.
- `models/`: Saved PyTorch models for reuse or deployment.
- `README.md`: Documentation for the project.

---

## 📝 Dataset

The dataset used for this project was sourced from Google and contains labeled X-ray images. Categories include:
- **Healthy**: X-rays of lungs without infection.
- **Infected**: X-rays showing signs of infection.

Images were resized and normalized during preprocessing to ensure consistency.

---

## 📊 Output

- **Metrics**: Training and validation accuracy, loss, and confusion matrices.
- **Plots**: Visualizations of accuracy and loss over epochs for better understanding of model performance.
- **Saved Models**: Trained PyTorch models saved for further usage.

---

## 🤝 Contribution

Contributions are welcome! Fork the repository and open a pull request with your improvements.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgments

Special thanks to the contributors of PyTorch and the open-source datasets available online. 🎉
