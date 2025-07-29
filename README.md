# 🧠 Sentiment Analysis Using TextBlob and VADER 

This project presents a comprehensive sentiment analysis pipeline using Natural Language Processing (NLP) techniques and lexicon-based models—**TextBlob** and **VADER**—to classify short text data into **Positive**, **Negative**, or **Neutral** sentiments. The implementation simulates real-world applications like analyzing tweets, customer reviews, and public feedback to extract valuable emotional insights.

---

## 🔍 Objective

To analyze textual data using NLP techniques and classify each entry by its sentiment polarity. This helps identify public opinion and emotional trends that can be leveraged in product development, social research, or marketing campaigns.

---

## 📌 Key Features

- ✅ Cleaned and preprocessed textual data using NLTK and regex
- ✅ Applied **TextBlob** to generate polarity-based sentiment labels
- ✅ Applied **VADER** (Valence Aware Dictionary and sEntiment Reasoner) for emotion-sensitive sentiment scoring
- ✅ Compared predicted results from both models with original labels
- ✅ Visualized sentiment distributions using Seaborn plots
- ✅ Extracted actionable insights on public sentiment patterns

---

## 🧪 Technologies Used

- **Python 3**
- **Google Colab**
- **Pandas, Numpy**
- **NLTK, TextBlob, VADER**
- **Matplotlib, Seaborn**

---

## 📁 Files Included

| File Name                                   | Description                                      |
|--------------------------------------------|--------------------------------------------------|
| `Sentiment_Analysis_TextBlob_VADER_Task4.ipynb` | Full Jupyter notebook with code, plots, and outputs |
| `twitter_sentiment_data.csv`               | Clean CSV dataset with text and sentiment labels |

---

## 📈 Step-by-Step Process

1. **Data Loading:** Imported a CSV file containing tweet-style text entries with original sentiment labels.
2. **Data Exploration:** Checked for missing values, class distribution, and types.
3. **Text Cleaning:** Removed punctuation, stopwords, special symbols, links, and converted to lowercase.
4. **TextBlob Analysis:** Calculated polarity scores and mapped them to sentiment classes.
5. **VADER Analysis:** Applied VADER compound scores to classify sentiments.
6. **Result Comparison:** Stored model predictions and compared them with actual labels.
7. **Visualization:** Created side-by-side sentiment distribution plots for original, TextBlob, and VADER results.
8. **Insights Extraction:** Interpreted model behavior and outlined key takeaways.

---

## 📊 Visual Output Samples

- Distribution of original sentiments vs predicted ones
- TextBlob’s conservative predictions (more neutral classifications)
- VADER’s sensitivity to expressive or social tone (more positive predictions)

---

## 💡 Key Insights

- **TextBlob** performs well on formal or balanced text data.
- **VADER** is better suited for informal, emotion-rich texts like tweets.
- Lexicon-based models offer fast and interpretable solutions for sentiment tasks, especially in real-time systems.
- Visual comparisons reveal bias or skew in model predictions, which can inform model choice in practical deployments.

---

## 📌 Applications

- Social media sentiment tracking
- Brand reputation monitoring
- Customer review mining
- Trend detection and public opinion analysis

---

## 📚 Acknowledgment

This project is developed as part of the **Data Analytics Internship at CodeAlpha**. It demonstrates a hands-on application of NLP techniques and lexicon models in real-world sentiment classification.

---

## 🔗 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com)
2. Upload the `twitter_sentiment_data.csv` file when prompted
3. Run cells step-by-step to view results, graphs, and interpretations





