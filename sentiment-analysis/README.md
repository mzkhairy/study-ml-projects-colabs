# AI-Powered Sentiment Analysis of Automotive YouTube Comments

**Status:** Completed University Project

### Objective
This project was designed to build an end-to-end Natural Language Processing (NLP) pipeline that can automatically crawl, clean, and analyze comments from automotive YouTube videos specifically for videos with bahasa indonesia. The goal is to extract meaningful patterns and provide actionable insights on viewer sentiment, helping content creators improve their strategy.

### Key Features & Methodology
* **Web Crawling:** Utilized the `youtube-comment-downloader` library to gather hundreds of real-world comments.
* **Data Pre-processing:** Implemented advanced data cleaning functions to handle informal language, filter spam, and create a domain-specific vocabulary for the automotive industry.
* **Sentiment Analysis:** Leveraged a pre-trained Hugging Face Transformer model (`taufiqdp/indonesian-sentiment`) to classify comments as positive, negative, or neutral.
* **Insight Generation:** The system automatically categorizes comments by vehicle features (e.g., exterior, performance, reliability) and generates data visualizations like word clouds and sentiment distribution charts.

### Tech Stack
* **Languages & Libraries:** Python, Pandas, NLTK, Scikit-learn
* **AI/ML:** Hugging Face Transformers, PyTorch
* **Environment:** Google Colab

### View the Project
The complete code, analysis, and visualizations are available in the Google Colab notebook.

➡️ **[View the full analysis in Google Colab](https://colab.research.google.com/drive/1VcmxVuzgmD_igbss_nLAd8dNBiZYL3Qr?usp=sharing)**
