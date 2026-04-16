<div align="center">
  
  # 🧠 Sentiment Analysis using RNN

  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
  [![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://tensorflow.org)
  [![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)](https://keras.io)
  [![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
  [![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)

  *A deep learning project for classifying customer reviews into positive or negative sentiments using RNNs.*
</div>

---

## 📖 Overview
This project performs **sentiment analysis** on customer reviews using a **Recurrent Neural Network (RNN)**.  

The model learns sequential patterns in text data to classify reviews as **positive or negative**, enabling automated opinion analysis.

---

## 🚀 Features
- 🧹 Text preprocessing (cleaning, tokenization, padding)  
- 🔤 Word embedding for semantic representation  
- 🤖 RNN-based deep learning model  
- 📊 Binary sentiment classification  
- 📉 Train/validation/test evaluation  

---

## 📊 Dataset
- **Source:** Customer review dataset  
- **File Name:** `swiggy.csv`  

### 🏷️ Labeling Logic
- **Positive (1):** Rating > 3.5  
- **Negative (0):** Rating ≤ 3.5  

---

## 🛠️ Preprocessing Steps
- Convert text to lowercase  
- Remove punctuation & special characters  
- Tokenize reviews into sequences  
- Apply padding for uniform input length  

---

## 🧠 Model Architecture
- **Embedding Layer** → Converts words into dense vectors  
- **SimpleRNN Layer** → Captures sequential dependencies  
- **Dense Layer (Sigmoid)** → Outputs binary classification  

---

## 📂 Project Structure
```text
.               # Model training script
├── Sentiment_Analysis_with_an_Recurrent_Neural_Networks_(RNN).ipynb
└── swiggy.csv
└── README.md
```
## 📈 Results
- 📊 Accurate sentiment classification on customer reviews  
- 🧠 Learns contextual dependencies in text  
- ⚡ Efficient baseline model for NLP tasks  

---

## 📌 Future Enhancements
- 🔁 Upgrade to LSTM / GRU / Transformers  
- 🌐 Deploy using Streamlit or Flask  
- 📚 Use pre-trained embeddings (GloVe, Word2Vec)  
- 🎯 Multi-class sentiment classification  

---

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

---
