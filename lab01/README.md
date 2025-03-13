# **Machine Learning Project: Regression Analysis on Housing Prices**

## **Overview**
Understanding relationships between different factors is crucial for businesses and organizations to make data-driven decisions. Regression analysis helps quantify these relationships between numerical features, allowing for forecasting and decision-making.

This project applies **regression modeling techniques** to a real-world dataset to predict home values based on key features. You will:

- Load and explore a housing dataset.
- Select relevant features for predicting the target variable.
- Train a **Linear Regression model** and evaluate its performance.
- Compare different regression techniques.
- Document your findings in a structured Jupyter Notebook.

## **Dataset**
We use the **California Housing Prices Dataset**, a built-in dataset from `scikit-learn`:

Additionally, alternative housing price datasets are available on **Kaggle**.

## **Technology Stack**
This project utilizes **Python** and essential **machine learning libraries**:

- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computing
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning library for regression modeling

For more information, visit [Scikit-learn Documentation](https://scikit-learn.org/).

### **Professional Python Development Workflow**
We adhere to professional Python practices for development. Full instructions can be found at [pro-analytics-01](https://github.com/denisecase/pro-analytics-01/).

**⚠️ Important:**  
VS Code + Pylance may sometimes fail to recognize installed packages in Jupyter notebooks. See the **Workflow Guide (WORKFLOW_GUIDE.md)** for troubleshooting.

---

## **Project Outline**
This project follows a structured approach in machine learning:

### **Section 1: Load and Explore the Data**
- **1.1** Load the dataset and display the first 10 rows.
- **1.2** Check for missing values and summary statistics.
- **🔍 Analysis:** Identify potential data issues or anomalies.

### **Section 2: Visualize Feature Distributions**
- **2.1** Create **histograms, boxplots, and scatterplots**.
- **2.2** Identify patterns and anomalies in feature distributions.
- **🔍 Analysis:** Highlight key observations from visualizations.

### **Section 3: Feature Selection and Justification**
- **3.1** Choose **two input features** (`MedInc`, `AveRooms`) for prediction.
- **3.2** Justify the selection with reasoning.
- **🔍 Analysis:** Explain why these features are relevant for predictions.

### **Section 4: Train a Linear Regression Model**
- **4.1** Define `X` (features) and `y` (target variable).
- **4.2** Train a **Linear Regression model** using Scikit-Learn.
- **4.3** Evaluate model performance using **R², MAE, RMSE**.
- **🔍 Analysis:** Assess model accuracy and insights.

---

## **Project Files**
- 📂 **`applied-ml-jballard.ipynb`** – Jupyter Notebook with data exploration, model training, and evaluation.
- 📄 **`requirements.txt`** – List of required Python libraries.
- 📄 **`README.md`** – Project documentation (this file).
- 📄 **`.gitignore`** – Ensures unnecessary files (e.g., `.venv`) are excluded from Git.

---

## **Running the Notebook Locally**
### **1. Clone the repository**
```sh
git clone 
cd ml-01
```

### **2. Create and activate a virtual environment**
```sh
python -m venv .venv
source .venv/bin/activate  # For macOS/Linux
# OR
.venv\Scripts\activate  # For Windows
```

### **3. Install dependencies**
```sh
pip install -r requirements.txt
```

### **4. Run Jupyter Notebook**
```sh
jupyter notebook
```
Open `ml-01.ipynb` and run the code.

---

## **Checklist Before Submission**
✔ **Ensure your repository includes the following:**
- ✅ **`.gitignore`** (excluding `.venv`)
- ✅ **A well-structured Jupyter Notebook** with clear section numbering.
- ✅ **A professional `README.md`** (this file).
- ✅ **A complete `requirements.txt`** for dependency management.

---

## **Contributors**
👤 **Jason Ballard**  
📅 **March 12, 2025**  
📌 **GitHub Profile:** [Jason Ballard Git HUb Profile](https://github.com/JBtallgrass)

---

## **License**
This project is open-source