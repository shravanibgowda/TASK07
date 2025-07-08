Breast Cancer Classification using SVM

This project involves building a machine learning model to classify breast cancer cases as malignant or benign using Support Vector Machine (SVM).

Dataset

The dataset used is the **Breast Cancer Wisconsin dataset**, which contains features computed from digitized images of fine needle aspirate (FNA) of breast masses.

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

Features

The dataset contains numerical values representing characteristics of cell nuclei such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- ... and more.

Project Structure

- **Data Loading and Exploration**: Importing the dataset and examining its structure and statistics.
- **Preprocessing**: Handling missing values, encoding labels, and scaling features.
- **Model Training**: Training an SVM classifier.
- **Model Evaluation**: Assessing the model's performance using metrics like accuracy, confusion matrix, and classification report.
- **Hyperparameter Tuning**: Using GridSearchCV for optimal model performance.

Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Usage

1. Clone this repository or download the `.ipynb` file.
2. Ensure all required libraries are installed (`pip install -r requirements.txt`).
3. Run the notebook cell by cell to see the workflow and results.

Results

The SVM model was trained and tuned to accurately classify breast cancer types with high accuracy.

