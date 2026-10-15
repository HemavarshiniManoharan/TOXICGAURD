# 🛡️ ToxiGuard – Toxic Comment Detection Using NLP and BiLSTM

### 1. Project Title

🛡️ ToxiGuard – Toxic Comment Detection Using NLP and Bidirectional LSTM

An NLP and deep learning project developed using Python to detect and classify toxic comments into six categories using text analytics and a Bidirectional LSTM model.

---

### 2. Short Description

ToxiGuard is a toxic comment detection project designed to identify harmful language in online comments through Natural Language Processing and deep learning.

The project involves data cleaning, exploratory data analysis, text preprocessing, tokenization, and sequence padding. A TF-IDF with Logistic Regression baseline and a Bidirectional LSTM model are used for multi-label classification to identify different types of toxicity.

---

### 3. Tech Stack

- 🐍 **Python** – Used for data processing and model development.
- 🧹 **Pandas** – Used for data cleaning and manipulation.
- 🔢 **NumPy** – Used for numerical operations.
- 📊 **Matplotlib** – Used to visualize data patterns.
- 📈 **Seaborn** – Used for statistical visualization and EDA.
- 🤖 **Scikit-learn** – Used for TF-IDF, Logistic Regression, data splitting, and evaluation.
- 🧠 **TensorFlow/Keras** – Used to build and train the BiLSTM model.
- ☁️ **Google Colab** – Used to develop and execute the project.

---

### 4. Data Source

The project uses the **Jigsaw Toxic Comment Classification dataset**, which contains online comments labeled across six toxicity categories:

- Toxic
- Severe Toxic
- Obscene
- Threat
- Insult
- Identity Hate

The dataset contains 159,571 comments and was explored to understand label distributions, comment lengths, common words, and class imbalance.

---

### 5. Features

- 🧹 Data Cleaning and Preprocessing
- 🔍 Data Quality Analysis
- 📊 Univariate and Bivariate Analysis
- 📈 Comment Length Analysis
- 🔤 Frequent Word Analysis
- ⚖️ Class Imbalance Analysis
- ✍️ Text Cleaning and Normalization
- 🔠 Tokenization and Sequence Padding
- 🤖 TF-IDF Vectorization
- 📐 Logistic Regression Baseline Model
- 🧠 Bidirectional LSTM Model
- 🎯 Multi-Label Toxic Comment Classification
- 📊 Model Evaluation and Prediction Testing

---

### Business Problem

Online platforms receive large volumes of user comments, making it difficult to manually identify toxic or harmful language. Different types of toxicity can also occur within the same comment, requiring an effective automated classification approach.

### Goal of the Project

The goal is to analyze comment text and develop machine learning and deep learning models that can identify six types of toxicity through multi-label classification.

### Key Analysis Areas

- Toxicity Label Distribution
- Toxic vs. Non-Toxic Comments
- Comment Length Distribution
- Frequent Word Analysis
- Class Imbalance Investigation
- Text Preprocessing and Tokenization
- TF-IDF Feature Extraction
- Logistic Regression Baseline
- Bidirectional LSTM Model Development
- Validation Performance Evaluation
- Predictions on New Comments

### Key Outcomes & Insights

The project supports:

- Understanding patterns in toxic and non-toxic comments
- Identifying class imbalance across toxicity categories
- Applying NLP techniques to transform text into numerical sequences
- Comparing a traditional machine learning baseline with a deep learning approach
- Building a multi-label classification model for six toxicity categories
- Testing model predictions on new comments
- Developing practical skills in NLP, deep learning, and model evaluation

---

## 📁 Project Files

- `ToxiGuard_Toxic_Comment_Detection.ipynb` – Notebook containing data preprocessing, EDA, model development, evaluation, and prediction testing.
- `README.md` – Project documentation.
- `toxiguard_bilstm.keras` – Saved BiLSTM model, if included in the repository.
- `toxiguard_tokenizer.pkl` – Saved tokenizer, if included in the repository.
- `toxiguard_config.json` – Model configuration and label information, if included in the repository.

---

## ▶️ How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Download the Jigsaw Toxic Comment Classification dataset and upload `train.csv`.
4. Update the dataset path in the notebook if necessary.
5. Run the notebook cells sequentially to reproduce the analysis and model workflow.

---

## 📷 Project Preview

The notebook contains Python code, EDA visualizations, text preprocessing steps, model training results, evaluation outputs, and predictions on sample comments.

To explore the complete workflow, open the notebook file in this repository.

---

## 🛠️ Tools Used

**Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | TensorFlow | Keras | NLP | TF-IDF | Logistic Regression | BiLSTM | Multi-Label Classification | Google Colab**

---

## 👩‍💻 Author

**Hemavarshini Manoharan**

[GitHub](https://github.com/HemavarshiniManoharan) | [LinkedIn](https://www.linkedin.com/in/hemavarshini-m-1b95072b3/)
