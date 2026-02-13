# Machine Learning Labs and Assignments Repository

This repository contains a collection of lab experiments, assignments, datasets, and code implementations for a machine learning course. The files cover topics such as data sources, exploratory data analysis (EDA), data visualization, preprocessing, classification (KNN, Naive Bayes, Decision Trees, SVM, etc.), clustering (Spectral, DBSCAN, K-Means), regression (Linear, Logistic), and performance evaluation. The materials are primarily in Jupyter notebooks (.ipynb), Word documents (.docx), and CSV datasets.

The focus is on practical implementations using Python libraries like pandas, scikit-learn, matplotlib, and seaborn. Datasets include topics like kids' screen time, healthcare stroke data, wine clustering, and a custom pharma industry survey.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Datasets](#datasets)
- [Labs and Notebooks](#labs-and-notebooks)
- [Assignments and Reports](#assignments-and-reports)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- **Python 3.x**
- **Jupyter Notebook** or **JupyterLab** (for running .ipynb files)
- **Required libraries**: Install via `pip install -r requirements.txt` (create one if needed, or see below).

Key libraries used:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `sympy` (for some math-related labs)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn sympy
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   Open and run the `.ipynb` files in your browser.

## Usage

- **Run Notebooks**: Open any `.ipynb` file in Jupyter and execute cells step-by-step. Most notebooks include data loading, preprocessing, model training, evaluation, and visualizations.
- **View Reports**: Open `.docx` files using Microsoft Word or compatible software (e.g., LibreOffice) for lab theories, steps, and conclusions.
- **Datasets**: CSV files can be loaded directly in notebooks or explored with tools like Excel.
- **Tools Integration**: Some notebooks use advanced tools like code execution for simulations or web searches.

**Example: To run `lab-5.ipynb` (Boosting Classifiers):**
1. Ensure `Indian_Kids_Screen_Time.csv` is in the folder.
2. Open the notebook and run all cells to see preprocessing, model training, and accuracy comparisons.

*Note: Adjust file paths if datasets are moved. Some notebooks assume datasets are in the same directory.*

## File Structure

```text
.
├── datasets/                # CSV datasets
│   ├── response.csv
│   ├── healthcare-dataset-stroke-data.csv
│   ├── Indian_Kids_Screen_Time.csv
│   └── ... (other CSVs if any)
├── labs/                    # Jupyter notebooks for labs
│   ├── lab-1.ipynb
│   ├── lab-2.ipynb
│   ├── lab-3.ipynb
│   ├── lab-4.ipynb
│   ├── lab-5.ipynb
│   ├── lab-6.ipynb
│   ├── lab-7.ipynb
│   └── ... (other labs)
├── reports/                 # Word documents for labs and assignments
│   ├── Lab - 1.1.docx
│   ├── Lab - 1.2.docx
│   ├── Lab - 2.docx
│   ├── ML Assignment.docx
│   └── ... (other reports)
├── README.md                # This file
└── requirements.txt         # (Optional: Add Python dependencies)
```
*(Note: Organize files into subfolders like above for better structure before uploading to GitHub.)*

## Datasets

- `response.csv`: Survey responses on pharma industry awareness (e.g., age groups, knowledge of reactors).
- `healthcare-dataset-stroke-data.csv`: Stroke prediction dataset with features like age, hypertension, glucose levels.
- `Indian_Kids_Screen_Time.csv`: Data on children's screen time, devices, health impacts.
- `wine-clustering.csv` (implied in labs): Wine quality dataset for clustering tasks.
- `ML Assignment.docx` includes a custom dataset description for pharma survey.

These are used for EDA, classification, clustering, and regression experiments.

## Labs and Notebooks

- **lab-1.ipynb**: Data loading, independent/dependent features, rows display (5-17), cleaning (missing/duplicates), visualization (box/scatter/hist/pie/KDE plots), encoding (one-hot/label).
- **lab-2.ipynb**: KNN and Naive Bayes implementation, metrics comparison (accuracy, precision, recall, F1), confusion matrices.
- **lab-3.ipynb**: Cross-validation with Decision Trees and Random Forests.
- **lab-4.ipynb**: SVM, Decision Trees (Gini/Entropy/Log Loss), Random Forest, Gradient Boosting; accuracy comparison.
- **lab-5.ipynb**: Boosting classifiers (AdaBoost, Gradient Boosting) on screen time data.
- **lab-6.ipynb**: Clustering (Spectral, DBSCAN, K-Means) on wine dataset, silhouette scores, visualizations.
- **lab-7.ipynb**: Regression (Linear, Logistic, Ridge, Lasso), error metrics (MSE, RMSE, MSLE).
- **ml_lab3.ipynb**: Additional lab on stroke data (similar to lab-3).
- **MLlabassignement4 (1).ipynb**: SVM and tree-based models on stroke data.

Each notebook includes code, outputs, and explanations. Visualizations often use matplotlib/seaborn for plots like confusion matrices and cluster scatters.

## Assignments and Reports

- **Lab - 1.1.docx**: Data sources (public/private/government), EDA, visualization.
- **Lab - 1.2.docx**: Dataset import, cleaning, visualization, encoding explanations.
- **Lab - 2.docx**: KNN & Naive Bayes guide, metrics explanation.
- **ML Assignment.docx**: Custom dataset creation for pharma survey (features like age, gender, knowledge).

These documents provide theoretical background, steps, and conclusions for the labs.

## Contributing

Feel free to fork this repository and submit pull requests for improvements, bug fixes, or additional labs. Ensure code is well-commented and follows PEP8 standards.

## License

This repository is licensed under the MIT License. See `LICENSE` for details (add a `LICENSE` file if needed). Datasets may have their own licenses; check sources like Kaggle for usage rights.
