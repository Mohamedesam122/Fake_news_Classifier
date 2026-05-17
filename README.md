# 📰 Fake News Detection using NLP & Machine Learning

An AI-powered Fake News Detection system built using Natural Language Processing (NLP), TF-IDF vectorization, and Machine Learning algorithms.

The project analyzes news articles and predicts whether the news is **Fake** or **Real** with an interactive and modern deployment interface using Streamlit.

---

# 🚀 Features

- Text preprocessing and cleaning
- Stopwords removal and stemming
- TF-IDF feature extraction
- Fake vs Real news classification
- Interactive visualizations
- Model evaluation metrics
- Streamlit web application
- Beautiful UI/UX dashboard
- Explainable AI insights

---

# 📂 Dataset

The dataset contains:
- News title
- Author
- News content
- Label
  - `0` → Real News
  - `1` → Fake News

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Plotly
- WordCloud
- Streamlit

---

# 🧹 NLP Preprocessing

The text preprocessing pipeline includes:

- Lowercasing
- Removing punctuation and special characters
- Removing stopwords
- Stemming using PorterStemmer
- Tokenization
- TF-IDF vectorization

---

# 📊 Exploratory Data Analysis (EDA)

Several visualizations were created to better understand the dataset:

- Fake vs Real news distribution
- Word count analysis
- Text length distribution
- Word clouds
- Top frequent words
- N-gram analysis

---

# 🤖 Machine Learning Pipeline

## 1. Data Cleaning
Text preprocessing using regex and NLTK.

## 2. Feature Extraction
TF-IDF Vectorization with unigrams and bigrams.

## 3. Model Training
Machine Learning classification models were trained on the processed dataset.

## 4. Model Evaluation
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

# 📈 Model Performance

The model achieved strong performance in detecting fake news articles using NLP techniques and TF-IDF features.

---

# 🌐 Streamlit Deployment

The project includes a professional Streamlit web application where users can:

- Paste news articles
- Predict Fake or Real news
- View confidence scores
- Explore NLP insights and visualizations

Run the app locally:

```bash
streamlit run app.py
```

---

# 📁 Project Structure

```text
Fake-News-Detection/
│
├── app.py
├── fake_news_model.pkl
├── tfidf_vectorizer.pkl
├── requirements.txt
├── README.md
├── notebook.ipynb
├── dataset/
│   └── train.csv
│
├── assets/
│   ├── images
│   └── animations
│
└── pages/
    ├── Home.py
    ├── Prediction.py
    ├── Dashboard.py
    └── About.py
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/fake-news-detection.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

# 📌 Future Improvements

- Deep Learning models (LSTM / GRU)
- BERT and Transformer models
- SHAP Explainability
- Attention visualization
- Real-time news API integration
- Multi-language fake news detection

---

# 👨‍💻 Author

Developed by Mohamed Essam

---

# ⭐ If you like this project

Give it a star on GitHub and feel free to contribute.
