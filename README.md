# 🧠 DAML — Data Analysis & Machine Learning Platform

A powerful, user-friendly platform built with **Streamlit** that enables users to learn, explore, and perform end-to-end **Data Analysis**, **Visualization**, and **Machine Learning** with minimal coding. Ideal for students, educators, and analysts looking for hands-on ML practice in an interactive environment.

---

## 🚀 Features

- 📊 **Learn Mode**: Educational content explaining key data science and ML concepts.
- 🔍 **Data Analysis**: Upload datasets, handle missing values, explore correlations, and generate descriptive stats.
- 📈 **Visualization Tools**: Create histograms, boxplots, heatmaps, and scatter plots for deep insights.
- 🤖 **ML Modules**:
  - **Regression**: Apply and compare models like Linear Regression and Ridge.
  - **Classification**: Use Logistic Regression, Decision Trees, Random Forests, and more.
  - **Clustering**: Perform unsupervised learning with KMeans, Agglomerative, and DBSCAN.

---

## 🛠️ Tech Stack

- **Frontend & UI**: Streamlit
- **Backend Logic**: Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- **IDE**: VS Code, Cursor

---

## ⚙️ Installation

### 🔗 Clone the Repository

```bash
git clone https://github.com/cj404-proj/DAML.git
cd DAML
```

### 🐍 Create & Activate a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 📦 Install Requirements

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the App

```bash
streamlit run 1_Home.py
```

Open the URL in your browser (usually `http://localhost:8501`).

---

## 📁 Folder Structure

```
DAML/
│
├── 1_Home.py              # Main entry point
├── requirements.txt
├── README.md
└── pages/
    ├── 2_Learn.py
    ├── 3_Analyse.py
    ├── 4_Regression.py
    ├── 5_Classification.py
    ├── 6_Clustering.py
```

---
