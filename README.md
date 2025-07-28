# 🤖 Machine Learning Lab Practices

<div align="center">

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Practice%20Lab-blue?style=for-the-badge&logo=python)
![Academic Year](https://img.shields.io/badge/Academic%20Year-2024--25-green?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.12.3-yellow?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?style=for-the-badge&logo=jupyter)

*Comprehensive collection of Machine Learning laboratory practices and assignments*

</div>

---

## 📚 About This Repository

This repository contains a comprehensive collection of laboratory practices (PL - Prácticas de Laboratorio) for the **Machine Learning** course at A Coruña Campus, academic year 2024-25. The practices cover fundamental machine learning concepts from exploratory data analysis to advanced clustering algorithms, all implemented from scratch using Python and popular data science libraries.

> 🔗 **Additional Project:** The most complex assignment (PLE03) is housed in a [separate repository](https://github.com/VforVitorio/PLE03) due to its advanced scope and technical requirements.

**Student:** Víctor Vega Sobral  
**Professor:** Borja González Seoane  
**Course:** G24GXX3.10X. Aprendizaje Automático

---

## 🗂️ Repository Structure

```
📁 Aprendizaje-Automatico/
├── 📁 S01/          # Session 01 - Environment Setup & EDA
├── 📁 S02/          # Session 02 - Data Preprocessing  
├── 📁 S04/          # Session 04 - Linear Regression
├── 📁 S05/          # Session 05 - Linear Discriminant Analysis
├── 📁 S06/          # Session 06 - Classification Models
├── 📁 S07/          # Session 07 - Course Materials
├── 📁 S08/          # Session 08 - Project Assignment (PLE02)
├── 📁 S010/         # Session 10 - Clustering Algorithms
└── 📄 README.md     # This file
```

---

## 📋 Detailed Session Contents

### 🔧 **Session 01 (S01) - Environment Setup & Exploratory Data Analysis**

> *Introduction to the course environment and data exploration fundamentals*

- **`pl00_demo_notebook.ipynb`** - Demo notebook showcasing Jupyter environment
- **`pl01_eda_pinguinos_Victor.ipynb`** - Comprehensive EDA of Palmer Penguins dataset
- **`palmer_penguins.csv`** - Palmer Penguins dataset
- **`Configuración prácticas de laboratorio.pdf`** - Lab setup instructions

**Key Topics:**

- Jupyter Notebook environment setup
- Exploratory Data Analysis (EDA) techniques
- Data visualization with matplotlib and seaborn
- Statistical analysis and data understanding

---

### 🔄 **Session 02 (S02) - Data Preprocessing & Normalization**

> *Data preprocessing techniques and feature engineering*

- **`pl02_normalizacion_estandarizacion.ipynb`** - Normalization and standardization techniques
- **`PLE01_Vega_Sobral_Victor.ipynb`** - First assignment: TripAdvisor reviews analysis
- **`tripadvisor_review.csv`** - TripAdvisor reviews dataset
- **`palmer_penguins.csv`** - Palmer Penguins dataset (continued from S01)
- **`PLE01.pdf`** - Assignment instructions
- **`Analisis-Exploratorio-de-Datos-de-Resenas-de-TripAdvisor (1).pptx`** - EDA presentation

**Key Topics:**

- Data normalization and standardization
- Feature scaling techniques
- Data preprocessing pipelines
- TripAdvisor review data analysis

---

### 📈 **Session 04 (S04) - Linear Regression Implementation**

> *From-scratch implementation of linear regression using derivatives*

- **`pl03_rlu_derivadas.ipynb`** - Univariate linear regression implementation from scratch

**Key Topics:**

- Mathematical foundations of linear regression
- Derivative-based parameter optimization
- Comparison with scikit-learn LinearRegression
- Model evaluation metrics

---

### 🎯 **Session 05 (S05) - Linear Discriminant Analysis (LDA)**

> *Classification using Linear Discriminant Analysis*

- **`pl04_lda_5_pasos.ipynb`** - 5-step LDA implementation from scratch
- **`pl04_lda_sklearn.ipynb`** - LDA using scikit-learn

**Key Topics:**

- Linear Discriminant Analysis theory and implementation
- 5-step LDA algorithm breakdown
- Dimensionality reduction techniques
- Classification with Iris dataset
- Comparison between scratch and scikit-learn implementations

---

### 🏷️ **Session 06 (S06) - Classification Models Comparison**

> *Multiple classification algorithms and model comparison*

- **`pl05_clasificacion_varios_modelos.ipynb`** - Multi-model classification comparison
- **`pl05_rlo_scratch.ipynb`** - Logistic regression from scratch implementation
- **`titanic.csv`** - Titanic survival dataset

**Key Topics:**

- Logistic regression from scratch with gradient descent
- Support Vector Machines (SVM)
- Model comparison and evaluation
- Titanic survival prediction
- Binary classification techniques

---

### 📖 **Session 07 (S07) - Course Materials**

> *Theoretical materials and documentation*

- **`Transparencias U3-S07.pdf`** - Unit 3 theoretical slides

**Key Topics:**

- Advanced machine learning concepts
- Theoretical foundations

---

### 🎯 **Session 08 (S08) - Data Pipeline Project (PLE02)**

> *Complete data science pipeline implementation*

#### Main Directory:

- **`PLE02.pdf`** - Project assignment instructions
- **`ple02_Vega_Sobral_Víctor.zip`** - Complete project submission

#### Project Subdirectory (`PLE02/`):

- **`ple02_n01_eda.ipynb`** - Exploratory Data Analysis notebook
- **`ple02_n02_seleccion_modelo.ipynb`** - Model selection and evaluation
- **`ple02_gimnasio.csv`** - Original gym dataset
- **`ple02_gimnasio_procesados.csv`** - Processed gym dataset
- **`modelo_regresion_lineal.pkl`** - Trained linear regression model
- **`X_train.csv`, `X_test.csv`, `y_train.csv`, `y_test.csv`** - Training/testing splits
- **`requirements.txt`** - Project dependencies
- **`README.md`** - Project documentation

**Key Topics:**

- Complete data science pipeline development
- Calories burned prediction model
- Model serialization and deployment
- Data preprocessing and feature engineering
- Model evaluation and comparison (Linear Regression, Random Forest, SVR)

---

### 🎯 **Session 10 (S010) - Clustering Algorithms**

> *Unsupervised learning with clustering techniques*

- **`pl06_kmeans_scratch.ipynb`** - K-means implementation from scratch
- **`pl06_clusterizacion.ipynb`** - Clustering analysis with real datasets
- **`pl06_dbscan_clusterizacion.ipynb`** - DBSCAN clustering implementation
- **`datos_facebook.csv`** - Facebook Live Sellers dataset

**Key Topics:**

- K-means clustering from scratch
- DBSCAN clustering algorithm
- Elbow method for optimal cluster selection
- Facebook Live Sellers data analysis
- Comparison between clustering algorithms
- Unsupervised learning evaluation metrics

---

## 🛠️ Technologies & Libraries Used

<div align="center">

| Category                          | Libraries/Tools                         |
| --------------------------------- | --------------------------------------- |
| **Core Python**             | `numpy`, `pandas`                   |
| **Visualization**           | `matplotlib`, `seaborn`, `plotly` |
| **Machine Learning**        | `scikit-learn`                        |
| **Data Analysis**           | `scipy`, `ucimlrepo`                |
| **Model Persistence**       | `joblib`, `pickle`                  |
| **Development Environment** | `Jupyter Notebook`, `Python 3.12.3` |

</div>

---

## 🚀 Getting Started

### Prerequisites

- Python 3.12.3 or higher
- Jupyter Notebook or JupyterLab
- Git (for cloning the repository)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/VforVitorio/Aprendizaje-Automatico.git
   cd Aprendizaje-Automatico
   ```
2. **Install dependencies:**

   ```bash
   # For specific project (e.g., PLE02)
   cd S08/PLE02
   pip install -r requirements.txt

   # Or install common libraries manually
   pip install pandas scikit-learn matplotlib numpy seaborn plotly jupyter
   ```
3. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

---

## 📊 Key Learning Outcomes

By working through these laboratory practices, students will gain hands-on experience with:

- ✅ **Exploratory Data Analysis (EDA)** - Understanding data through visualization and statistics
- ✅ **Data Preprocessing** - Cleaning, normalizing, and preparing data for ML models
- ✅ **Supervised Learning** - Linear regression, logistic regression, LDA, SVM
- ✅ **Unsupervised Learning** - K-means and DBSCAN clustering
- ✅ **Model Implementation** - Building ML algorithms from scratch
- ✅ **Model Evaluation** - Comparing different algorithms and metrics
- ✅ **Data Science Pipeline** - End-to-end project development
- ✅ **Python for Data Science** - Practical programming skills

---

## 📈 Datasets Used

| Dataset                         | Session  | Description                              | Size        |
| ------------------------------- | -------- | ---------------------------------------- | ----------- |
| **Palmer Penguins**       | S01, S02 | Penguin species classification data      | 344 samples |
| **TripAdvisor Reviews**   | S02      | Tourism review ratings across categories | Variable    |
| **Iris**                  | S05      | Classic flower species classification    | 150 samples |
| **Titanic**               | S06      | Passenger survival prediction            | 891 samples |
| **Gym Calories**          | S08      | Workout calories burned prediction       | 973 samples |
| **Facebook Live Sellers** | S010     | Thai sellers' live streaming data        | Variable    |

---

## 🎓 Academic Context

This repository represents practical laboratory work for the Machine Learning course in the Computer Science program. Each session builds upon previous knowledge, progressing from basic data analysis to advanced machine learning implementations.

**Course Structure:**

- **Theoretical Foundation** - Mathematical concepts and algorithms
- **Practical Implementation** - Hands-on coding and experimentation  
- **Real-world Applications** - Working with actual datasets
- **Assessment Projects** - PLE01, PLE02, and PLE03 comprehensive assignments

---

## 📝 Assignment Highlights

### 🏆 **PLE01 - TripAdvisor Review Analysis**

Complete exploratory data analysis of TripAdvisor review data across multiple tourism categories in East Asia.

### 🏆 **PLE02 - Gym Calories Prediction Pipeline**

End-to-end data science project predicting calories burned during workouts, including:

- Data preprocessing and feature engineering
- Model selection among Linear Regression, Random Forest, and SVR
- Model serialization and deployment preparation
- Comprehensive evaluation and documentation

### 🏆 **PLE03 - Advanced Deep Learning Project** 
> 📌 **[Separate Repository](https://github.com/VforVitorio/PLE03)** - Due to its complexity and size

Advanced deep learning implementation focusing on neural networks and sophisticated machine learning techniques. This project was moved to a dedicated repository due to its comprehensive scope and technical complexity.

**Repository:** [github.com/VforVitorio/PLE03](https://github.com/VforVitorio/PLE03)

---

## 🤝 Contributing

This repository is primarily for academic purposes. However, suggestions and improvements are welcome:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 📄 License

This project is part of academic coursework and is intended for educational purposes. Please respect academic integrity guidelines when referencing this work.

---

## 👨‍💻 Author

**Víctor Vega Sobral**

- University: UIE A Coruña Campus
- Course: Machine Learning Subject (2024-25)
- GitHub: [@VforVitorio](https://github.com/VforVitorio)

---

## 🙏 Acknowledgments

- **Professor Borja González Seoane** - Course instructor and guidance
- **Universidad Intercontinental de la Empresa (UIE)** - Academic institution
- **Open Source Community** - For the amazing Python data science ecosystem

---

<div align="center">

**⭐ If you find this repository helpful, please consider giving it a star! ⭐**

*"The best way to learn machine learning is by doing machine learning"*

</div>
