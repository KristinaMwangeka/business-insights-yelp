# Business Insights from Yelp Reviews 🛍️

This project analyzes Yelp reviews to uncover insights into business- and city-level customer sentiment.
It demonstrates the use of Hugging Face transformers in a real-world business analytics case, combining sentiment analysis with zero-shot classification to explore both customer satisfaction and themes behind the reviews.

---

## 🔑 Key Features

* Sentiment analysis using DistilBERT (`distilbert-base-uncased-finetuned-sst-2-english`)
* Zero-shot classification to identify common themes using (facebook/bart-large-mnli)
* Aggregated insights at the **business** and **city** level
* Visualizations: Top & Bottom cities
* Exported CSVs for reproducibility

---

## 🛠 Tech Stack

* Python, Pandas, Matplotlib, Seaborn
* Hugging Face Transformers (sentiment + zero-shot classification)
* Google Colab (GPU)

---

## 📊 Output

* Businesses by positive sentiment
* Top & Bottom cities by positive sentiment with State as hue
* Theme breakdowns from zero-shot classification (e.g., service issues in low-positivity cities)

## 🚀 Why It Matters

Companies can use this analysis to:

* Identify high-performing business locations

* Detect specific recurring issues (e.g., service vs. pricing)

* Support data-driven expansion, redesign, and policy planning

