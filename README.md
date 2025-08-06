# Titanic Survival Prediction
This Data Science project explores the famous Titanic dataset to analyze passenger survival patterns and build a predictive machine learning model. It covers the complete data science pipeline, from data cleaning and visualization to modeling and evaluation.

## Dataset

- **Source**: [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- **File used**: `train.csv`

---

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## Project Workflow

1. **Data Exploration**  
   - Explored features like `Pclass`, `Sex`, `Age`, `SibSp`, `Fare`, `Embarked`
   - Checked for missing values and data types

2. **Data Cleaning**  
   - Filled missing `Age` values with median  
   - Dropped irrelevant columns like `Name`, `Cabin`, `Ticket`  
   - Handled missing `Embarked` values using mode  
   - Encoded categorical columns (`Sex`, `Embarked`)  

3. **Data Visualization**  
   - Survival count by gender
   - Survival count by class

4. **Model Building**  
   - Used `LogisticRegression` for the model  
   - Performed train-test split (80-20)  
   - Trained model and made predictions on test data  
   - Evaluated model using accuracy score  

---

## Sample Visualizations

- Bar plot: Survival rate by gender
- Histogram: Age distribution of survivors vs non-survivors
- Count plot: Class vs Survival

---

## Results

- **Model Used**: LogisticRegression
- **Achieved Accuracy**: ~80% on test set  
- The model was able to capture survival patterns reasonably well using basic passenger features.

---

## How to Run

1. Clone the repository or download the `.ipynb` file  
2. Open the notebook in Jupyter or Google Colab  
3. Download the Titanic dataset (`train.csv`) from repository or [Kaggle](https://www.kaggle.com/competitions/titanic/data)  
4. Run all cells from top to bottom
