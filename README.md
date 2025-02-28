# **News Recommendation System using Sentiment Analysis** 📰🔍
---
## Overview  
This project builds a **personalized news recommendation system** using **Sentiment Analysis and Deep Learning**, analyzing user tweets to suggest relevant news articles. By integrating **Natural Language Processing (NLP), Machine Learning (ML), and Deep Learning (DL)**, the system enhances accuracy by filtering recommendations based on the user's positive sentiments.

---

## 🔍 How It Works  
✅ Fetches **user tweets** via the **Twitter API**.  
✅ **Preprocesses tweets** using **NLTK, Spacy, and Pandas** (Tokenization, Lemmatization, Stemming, Stopword Removal).  
✅ **Performs Sentiment Analysis** using:  
   - **Lexicon-based models**: VADER, TextBlob  
   - **ML-based models**: ANN-LSTM, Naïve Bayes, SVM  
✅ **Clusters users based on interests** using **K-Means Clustering**.  
✅ **Scrapes news articles** from various sources using **BeautifulSoup**.  
✅ **Vectorizes text** using **TF-IDF** and calculates similarity using **Cosine Similarity**.  
✅ **Recommends news articles** based on sentiment-filtered user interests.  
✅ **Evaluates performance** using **Jaccard Similarity and RMSE**.  

---

## 📊 Results & Evaluation  
The system calculates two **Jaccard Similarity Scores**:  

- **With Sentiment Analysis**: Articles are recommended based on **positive sentiments only**.  
- **Without Sentiment Analysis**: Articles are recommended based **only on topic matching**.  

The results show that **sentiment-based recommendations have a higher accuracy and relevance score**.  

### **Comparison with Other Models**  
| Model                     | Accuracy | RMSE Score  | Jaccard Similarity |
|---------------------------|----------|------------|--------------------|
| Without Sentiment Analysis | Medium   | Higher RMSE | Lower Similarity  |
| With Sentiment Analysis   | High     | Lower RMSE  | Higher Similarity |

---
