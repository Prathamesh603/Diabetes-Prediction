# Diabetes Prediction using Machine Learning

This project uses machine learning to predict whether a person has diabetes or not based on a set of medical attributes like age, BMI, glucose level, and more. The model is built using Support Vector Machine (SVM), a powerful classification algorithm. It is trained and evaluated using the **PIMA Indians Diabetes Dataset**.

## Dataset
The dataset used in this project is the **PIMA Indians Diabetes Dataset**. It contains medical data for female patients and is used to predict the likelihood of diabetes based on specific features.

### Dataset Features:
- **Pregnancies**: Number of pregnancies
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg / height in m^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function (a measure of genetic risk)
- **Age**: Age of the patient
- **Outcome**: 1 if the patient has diabetes, 0 otherwise

## Steps involved in the project:
1. **Data Preprocessing**:
   - Loaded and explored the dataset.
   - Standardized the data using `StandardScaler`.
   - Split the data into features (`X`) and target (`Y`).
2. **Model Building**:
   - The dataset was split into training and testing data.
   - Used the **Support Vector Machine (SVM)** algorithm with a linear kernel for classification.
3. **Model Evaluation**:
   - Evaluated the model using accuracy scores on both training and testing data.
4. **Prediction**:
   - The trained model was used to predict diabetes for a given set of features.

## Libraries Used:
- `numpy` - For numerical operations.
- `pandas` - For data manipulation and analysis.
- `scikit-learn` - For machine learning algorithms and data preprocessing.
- `matplotlib` (optional for visualization, not used in the code).

## Installation

To install the necessary libraries and run the project, use the following commands:

```bash
pip install numpy pandas scikit-learn
