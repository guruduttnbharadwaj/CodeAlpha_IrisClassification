#  Iris Flower Classification 

## 📌 Overview
This project applies **Machine Learning** to the famous **Iris dataset**, one of the most well-known datasets in the data science community.  
The dataset contains 150 samples of iris flowers, each described by four features:  
- Sepal length (cm)  
- Sepal width (cm)  
- Petal length (cm)  
- Petal width (cm)  

The task is to classify the flowers into one of three species:
- **Setosa**
- **Versicolor**
- **Virginica**

---

## 🗂 Dataset
- Built-in dataset available in **scikit-learn**  
- 150 rows, 4 numerical features, 1 categorical target variable  
- Balanced dataset (50 samples per species)

---

## ⚙️ Tech Stack
- **Python**  
- **Pandas / NumPy** → data handling  
- **Matplotlib / Seaborn** → data visualization  
- **Scikit-learn (sklearn)** → model building and evaluation  

---

## 📈 Steps Performed
1. **Data Loading & Exploration**  
   - Loaded the Iris dataset from scikit-learn  
   - Converted into a Pandas DataFrame  
   - Added species labels for clarity  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized feature distributions  
   - Plotted pairplots to observe separation between species  
   - Generated correlation heatmap  

3. **Data Preprocessing**  
   - Train-test split (80-20)  
   - Feature scaling using StandardScaler  

4. **Model Building**  
   - Implemented **K-Nearest Neighbors (KNN)** classifier  
   - Experimented with different `k` values  

5. **Model Evaluation**  
   - Accuracy score  
   - Confusion matrix heatmap  
   - Classification report (precision, recall, F1-score)  

---

## 📊 Results
- Achieved **~95% accuracy** on the test set (may vary slightly due to train-test split).  
- Confusion Matrix shows correct classification for most samples.  
- Best performance typically occurs for **k between 3 and 7**.  

---

## 📷 Visualizations
### Pairplot of Features
*(shows clear separation of Setosa vs other species)*  

### Confusion Matrix
*(demonstrates high classification accuracy)*  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOURUSERNAME/CodeAlpha_IrisClassification.git
   cd CodeAlpha_IrisClassification
