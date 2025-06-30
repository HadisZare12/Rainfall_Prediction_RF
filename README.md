# 🌧️ Rainfall Prediction Using Random Forest

This project aims to predict rainfall events using meteorological data and a Random Forest Classifier. The goal is to build a robust model that can forecast whether it will rain tomorrow based on current weather conditions.

---

## 📌 Project Workflow

```
Data Collection → Exploratory Data Analysis (EDA) → Data Preprocessing → Train/Test Split → Model Training → Evaluation → Hyperparameter Tuning
```

---

## 🧠 Model Used

- **Algorithm**: Random Forest Classifier
- **Library**: scikit-learn

---

## 📊 Dataset

- The dataset contains various meteorological features such as:
  - Temperature
  - Humidity
  - Wind Speed/Direction
  - RainToday, RainTomorrow (target)

*Note: Dataset source and license info should be added here if available.*

---

## 🧪 Key Steps

### 🔍 Exploratory Data Analysis (EDA)

- Checked for missing values
- Visualized feature distributions
- Analyzed correlations

### 🧹 Data Preprocessing

- Handled missing data
- Categorical encoding
- Feature scaling (if needed)

### 🧬 Model Training & Evaluation

- Split into training and testing sets
- Trained Random Forest Classifier
- Evaluated performance using:
  - Accuracy
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)

---

## 🔧 Hyperparameter Tuning

- Used GridSearchCV to optimize parameters such as:
  - `n_estimators`
  - `max_depth`
  - `min_samples_split`
- Improved overall accuracy and model robustness.

---

## 📈 Results

- **Final Accuracy**: ~XX.X% (replace with actual)
- Model showed good performance on unseen data, especially in correctly identifying rainfall events.

---

## 📁 Project Structure

```
RainFall_Prediction.ipynb       # Main notebook
README.md                       # Project summary
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/rainfall-prediction.git
   cd rainfall-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook and run `RainFall_Prediction.ipynb`.

---

## 🧠 Future Work

- Try advanced models like XGBoost or LSTM for time-series
- Deploy as an API or Streamlit app
- Real-time integration with weather APIs

---

## 🧑‍💻 Author

**Hadis**  
[LinkedIn](https://linkedin.com/in/Hadis-Zare) | [GitHub](https://github.com/HadisZare12) | [Email](mailto:profi.hadiszare@gmail.com)
