# ChatGPT Reviews Analysis with Python

This project presents a **data-driven analysis** of ChatGPT user reviews using Python.  
It explores what users like and dislike about ChatGPT through **sentiment analysis**, **keyword extraction**, and **trend visualization**, offering valuable insights into user experience and satisfaction.

---

## Overview

The dataset contains user reviews of ChatGPT, including:
- **Textual feedback**
- **Ratings**
- **Review dates**

The objective of this analysis is to:
1. Understand the **overall sentiment** of users toward ChatGPT.
2. Identify **key themes and features** that users appreciate.
3. Highlight **common problems and areas of dissatisfaction**.
4. Examine how user sentiment **evolved over time**.
5. Calculate the **Net Promoter Score (NPS)** to measure user loyalty.

---

## Key Features

-  **Sentiment Analysis** using *TextBlob* to classify reviews as Positive, Neutral, or Negative  
-  **Keyword & Phrase Extraction** using *CountVectorizer* to identify popular terms and patterns  
-  **Negative Feedback Analysis** to uncover common user complaints  
-  **NPS Calculation** to estimate user satisfaction and loyalty  
-  **Trend Visualization** of sentiment changes over time using *Plotly*

---

## Tech Stack

- **Programming Language:** Python  
- **Libraries Used:**  
  - `pandas` — Data handling and cleaning  
  - `plotly` — Interactive visualizations  
  - `sklearn` — Feature extraction with CountVectorizer  
  - `textblob` — Sentiment analysis  
  - `collections` — Frequency counting  

---

## Dataset

The dataset used in this analysis contains:
- `Review`: User feedback text  
- `Ratings`: User rating (1–5 stars)  
- `Review Date`: Date of review submission  

> You can download the dataset from the provided source or replace it with your own review dataset for similar analysis.

---

## 📈 Analysis Workflow

1. **Data Cleaning:**  
   Handle null values and prepare textual data for analysis.

2. **Sentiment Analysis:**  
   Assign sentiment labels (Positive, Neutral, Negative) using *TextBlob* polarity scores.

3. **Positive Review Insights:**  
   Extract most frequent 2-3 word phrases from positive reviews to identify liked features.

4. **Negative Review Insights:**  
   Identify common complaints, such as app crashes, wrong answers, or performance issues.

5. **Problem Categorization:**  
   Group negative feedback into broader problem areas like Accuracy, Performance, and UI.

6. **Temporal Trend Analysis:**  
   Visualize sentiment changes over time to understand evolving user perception.

7. **Net Promoter Score (NPS):**  
   Compute NPS to quantify overall user loyalty and satisfaction.

---

## Results Summary

- **Overall Sentiment:** Majority of users shared *positive* feedback.  
- **Positive Highlights:** Users praised ChatGPT’s accuracy, usability, and educational benefits.  
- **Negative Feedback:** Common complaints include incorrect answers, app crashes, and performance lags.  
- **Net Promoter Score (NPS):** `64.35` — indicating a **high likelihood** of users recommending ChatGPT.  

---

## Visualizations

- Sentiment Distribution (Positive, Neutral, Negative)  
- Common Phrases in Positive & Negative Reviews  
- Common User Problems  
- Sentiment Trends Over Time  

> All visualizations are created using **Plotly** for interactivity and easy interpretation.

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/ChatGPT-Reviews-Analysis.git
