# Store Insights from Yelp Reviews 🛍️

This project analyzes Yelp reviews to uncover store- and city-level customer sentiment insights.
It demonstrates the use of Hugging Face transformers in a real-world business analytics case.

## Key Features
- Sentiment analysis using DistilBERT (`distilbert-base-uncased-finetuned-sst-2-english`)
- Aggregated insights at the store and city level
- Visualizations: Top/Bottom stores, Top cities, Sentiment map
- Exported CSVs for reproducibility

## Tech Stack
- Python, Pandas, Matplotlib, Seaborn
- Hugging Face Transformers
- Google Colab (GPU)

## Example Output
- Top 10 stores by positive sentiment
- Top 20 cities ranked by sentiment with state hue
- Interactive store sentiment map

## Why It Matters
Retailers can use this analysis to:
- Identify high-performing store locations
- Detect cities with potential service issues
- Support data-driven expansion planning
