# Sentiment Analysis of Amazon Fine Food Reviews

## 📌 Project Overview

This project performs sentiment analysis on Amazon Fine Food reviews using two different Natural Language Processing (NLP) approaches:

1. **Lexicon-based method (VADER)** - A rule-based sentiment analyzer
2. **Deep learning transformer model (RoBERTa)** - A state-of-the-art pretrained language model

The objective is to compare traditional sentiment analysis techniques with modern transformer-based models and highlight their strengths and limitations when applied to real-world customer reviews.

---

## 🧰 Technologies & Libraries

- **Programming Language:** Python
- **Data Handling:** Pandas, NumPy
- **NLP:** NLTK, Transformers (Hugging Face)
- **Deep Learning:** PyTorch
- **Visualization:** Matplotlib, Seaborn
- **Math & Utilities:** SciPy

---

## ▶️ How to Run the Project

1. Launch Jupyter Notebook:
```bash
jupyter notebook sentiment_analysis_amazon_reviews.ipynb
```

2. Run all cells sequentially to reproduce the full analysis and results

---

## 📊 Results & Insights

### VADER
- Fast and lightweight
- Performs well on short, explicit sentiment reviews
- Struggles with sarcasm and complex context

### RoBERTa
- Superior performance on complex and contextual language
- Handles negation, sarcasm, and long reviews more effectively
- More computationally intensive

**Key Finding:** Transformer-based models outperform lexicon-based approaches in most real-world cases.
---

## 📁 Project Structure

```
sentiment-analysis-amazon-reviews/
├── sentiment_analysis_amazon_reviews.ipynb
├── README.md
├── data/
│   └── amazon_reviews.csv
└── requirements.txt
```

---

## 👤 Author

**Mustapha**  
NLP & Data Science Enthusiast

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/sentiment-analysis-amazon-reviews/issues).

---

## ⭐ Show Your Support

If you found this project helpful, please give it a star!
