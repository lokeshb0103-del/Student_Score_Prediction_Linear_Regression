# Student Scores Prediction Using Linear Regression

## 📌 Project Overview
This project uses Machine Learning to predict students' scores based on the number of hours they study. A Linear Regression model is trained on a student study-hours dataset to learn the relationship between study time and scores.

## 🎯 Objectives
- Understand the relationship between study hours and student scores.
- Build a Linear Regression model using Python.
- Predict student scores based on study hours.
- Evaluate model performance using standard regression metrics.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

## 📂 Dataset
The dataset contains student study hours and their corresponding scores.

**Features:**
- `Hours` – Number of hours studied.
- `Scores` – Student score (target variable).

**Dataset Source:** Kaggle

*Credit goes to the original dataset creator on Kaggle for providing the dataset used in this project.*

## ⚙️ Project Workflow
1. Imported the required Python libraries.
2. Loaded the dataset using Pandas.
3. Separated the input feature (`Hours`) and target variable (`Scores`).
4. Split the dataset into training and testing sets using an 80:20 ratio.
5. Trained a Linear Regression model using Scikit-learn.
6. Predicted student scores using the trained model.
7. Evaluated the model using MAE, MSE, and R² score.

## 📊 Model Evaluation Results

| Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 2.8187 |
| Mean Squared Error (MSE) | 15.6678 |
| R² Score | 0.5810 |

### Interpretation
- **MAE:** The average absolute prediction error is approximately 2.82 score points.
- **MSE:** The average squared prediction error is approximately 15.67.
- **R² Score:** The model explains approximately 58.1% of the variation in student scores on the test set.

## 🚀 How to Run
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy scikit-learn matplotlib
   ```

3. Place the dataset file `Students.csv` in the project directory.
4. Open the Jupyter Notebook in Google Colab or a local Jupyter environment.
5. Run the notebook cells to train the model and evaluate its performance.

## 📚 What I Learned
- Fundamentals of supervised Machine Learning.
- Simple Linear Regression.
- Feature and target selection.
- Train-test splitting.
- Model training and prediction.
- Regression evaluation metrics.

## 🙏 Credits
- **Dataset:** Kaggle — credit to the original dataset creator.
- **Libraries:** Pandas, NumPy, Scikit-learn, and Matplotlib.
- **Development Environment:** Google Colab.

**Note:** Please add the exact Kaggle dataset URL and creator's name to this README so the original source is properly attributed.

## 👨‍💻 Author
Lokesh Babu
