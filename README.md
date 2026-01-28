# AI-Market-Trend-Consumer-Sentiment-Forecaster

## 🚀 Overview

The **AI Market Trend & Consumer Sentiment Forecaster** is a Python-based project that combines **market trend analysis** with **consumer sentiment analysis** to forecast potential market movements. By leveraging machine learning and natural language processing (NLP), the system analyzes both structured market data and unstructured text data (such as reviews or news) to generate meaningful insights.

This project is useful for analysts, researchers, and developers interested in understanding how consumer sentiment influences market trends.

## 🧠 Key Features

- 📊 Market trend forecasting using historical data  
- 🗣️ Consumer sentiment analysis using NLP techniques  
- 🔗 Integration of sentiment signals with market indicators  
- 📈 Trend spike detection for sudden sentiment changes  
- 🛠️ Modular and extensible Python codebase  
- 📊 Interactive dashboard for visualization

## 🔄 Project Workflow

The project follows a structured, step-by-step data processing and analysis pipeline to ensure accurate market trend forecasting and sentiment insights.

### 🧹 Step 1: Data Cleaning (`cleaning.py`)
- Cleaned raw datasets to remove noise, duplicates, missing values, and inconsistencies.
- Ensured data quality for reliable analysis and modeling.

### 🔗 Step 2: Data Merging
- Merged product and review data collected from **Amazon** and **Flipkart**.
- Created a unified dataset for cross-platform analysis.

### 📉 Step 3: Data Reduction
- Reduced dataset size after merging to handle large volumes of data efficiently.
- Removed redundant and less relevant records to improve processing speed and model performance.

### 🗂️ Step 4: Category Definition (`category.py`)
- Defined and assigned categories to the products/data points.
- Helped in structured analysis and category-wise sentiment comparison.

### 😊 Step 5: Sentiment Analysis (`sentiment.py`)
- Performed sentiment analysis on textual data.
- Assigned sentiment labels (positive, negative, neutral).
- Generated random dates to simulate real-world time-series sentiment trends.

### 🧠 Step 6: Topic Modeling
- Applied topic modeling techniques to identify hidden themes and patterns in the data.
- Helped understand major discussion topics influencing consumer sentiment.

## 🌐 API Integration Files

The project uses multiple APIs to fetch real-time and external data sources:

1. **`news_api.py`**  
   - Fetches market-related news articles for sentiment and trend analysis.

2. **`reddit.py`**  
   - Collects Reddit discussions and posts to capture public opinion and sentiment.

3. **`rapid.py`**  
   - Uses RapidAPI services to gather additional external data relevant to market trends.

## 📜 License
This project is licensed under the MIT License.
See the LICENSE file for more details.
