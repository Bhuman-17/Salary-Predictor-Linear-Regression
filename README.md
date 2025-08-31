
# 💼 Salary Predictor using Linear Regression  

This project demonstrates how to build and deploy a **Salary Predictor Web App** using **Linear Regression** in Python.  
It is a beginner-friendly project that explains the fundamentals of regression, model training, and prediction, along with deployment on **Streamlit Cloud**.  

🔗 **Live App:** [Salary Predictor - Streamlit](https://salary-predictor-linear-regression-naqcfbqhmatubn5ewywjzw.streamlit.app/)  

---

## 📘 Overview  

The **Salary Predictor** estimates a person's salary based on their **Years of Experience**.  
Using a simple **Linear Regression model**, it establishes a relationship between experience and salary, allowing us to make predictions for unseen data.  

This project is especially useful for:
- Beginners learning **Machine Learning (ML) basics**  
- Understanding **Linear Regression mathematics and implementation**  
- Learning how to deploy ML models as **interactive web applications**  

---

## 📂 Project Structure  

```

├── app.py                     # Streamlit web application
├── Salary\_Data.csv            # Dataset used for training
├── model.pkl                  # Saved Linear Regression model
├── requirements.txt           # Dependencies
└── README.md                  # Project documentation

````

---

## ⚙️ Features  

- 🧑‍💻 Input **Years of Experience** and get a predicted **Salary**  
- 📈 Built using **Linear Regression** from scikit-learn  
- 🎨 Simple and interactive **Streamlit interface**  
- ☁️ Deployed seamlessly on **Streamlit Cloud**  

---

## 📊 Dataset  

The dataset used is **Salary_Data.csv**, which contains:  
- **YearsExperience** → Independent variable (X)  
- **Salary** → Dependent variable (Y)  

Example data:  

| YearsExperience | Salary   |
|-----------------|----------|
| 1.1             | 39343.0  |
| 2.0             | 43525.0  |
| 3.2             | 60150.0  |
| 5.5             | 83088.0  |
| 9.0             | 105582.0 |

---

## 🚀 Installation & Setup  

### 1️⃣ Clone Repository  
```bash
git clone https://github.com/<your-username>/Salary-Predictor-Linear-Regression.git
cd Salary-Predictor-Linear-Regression
````

### 2️⃣ Create Virtual Environment (optional)

```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Streamlit App Locally

```bash
streamlit run app.py
```

---

## 🎯 Usage

1. Open the app in your browser (local or via Streamlit link).
2. Enter **Years of Experience** in the input box.
3. Click **Predict Salary**.
4. View the **predicted salary** instantly!

---

## 🔍 Behind the Scenes

1. **Data Preprocessing**:

   * Load dataset with Pandas
   * Split into **training** and **test** sets

2. **Model Training**:

   * Train a **Linear Regression** model from scikit-learn
   * Fit on `YearsExperience` vs `Salary`

3. **Model Saving**:

   * Export trained model using **pickle**

4. **Web App**:

   * Streamlit provides input form
   * Trained model makes predictions in real-time

---

## 📚 Learning Outcomes

By completing this project, you will:

* Understand **Linear Regression fundamentals**
* Learn how to train and evaluate regression models in **scikit-learn**
* Gain hands-on experience in **model deployment** with Streamlit
* Develop an end-to-end ML project workflow

---

## 🛠️ Tech Stack

* **Python 3.x**
* **Pandas** → Data handling
* **NumPy** → Numerical operations
* **scikit-learn** → Linear Regression model
* **Pickle** → Model saving/loading
* **Streamlit** → Web app interface

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

* Dataset inspired by basic ML tutorials
* scikit-learn for easy implementation of ML algorithms
* Streamlit for making deployment effortless
