# Bordeaux-Events-Analysis
Bordeaux Events Analysis — Web Data Collection, Processing, and Visualization

## Context

The city of Bordeaux hosts numerous cultural, sports, and economic events every month. This project demonstrates skills in web data collection, cleaning, enrichment, exploratory analysis, and visualization. The main notebook notebook.ipynb contains the code and Markdown explanations for each step.

## Objectives
- Scrape and collect event data for a given month (e.g., **September**).
- Structure information such as:
  - **Title**, **Date**, **Time**, **Venue**, **Category**, **Description**, **Source URL**
- Clean and normalize data:
  - Format dates, remove duplicates, standardize venue names
- Enrich the dataset with:
  - Automatic categorization, keyword extraction, optional geocoding
- Perform exploratory analysis:
  - Event frequency by category, most active venues, temporal distribution
- Visualize insights with clear and interpretable charts
## ⚙️ How to Run

### 1️⃣ Setup Environment
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```
# Recommended Dependencies

-pandas
-requests
-beautifulsoup4
-lxml
-tqdm
-scikit-learn
-matplotlib
-seaborn
-nltk or spacy (for keyword extraction)
-
python-dateutil
