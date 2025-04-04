# 🧠 Ultimate AI Tool Aggregator Dataset

This repository hosts the most comprehensive and evolving dataset of AI tools from across the web — aggregated from leading directories like Toolify.ai, Futurepedia, OpenTools.ai, and more.

## 🔍 Features

- Curated AI tool entries across categories like Writing, Dev, Health, Marketing, etc.
- Web scraping scripts to sync data from public sources
- Modular design: plug in new data sources or APIs
- Publicly available under CC BY-SA 4.0

## 📂 Structure

| Folder        | Purpose                               |
|---------------|----------------------------------------|
| `data/`       | Datasets in CSV, JSON, or Parquet      |
| `scripts/`    | Web scrapers, ETL, and data cleaners   |
| `docs/`       | Policies, citations, diagrams          |
| `notebooks/`  | Exploratory Data Analysis (optional)   |

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/ai-tool-aggregator-dataset.git
cd ai-tool-aggregator-dataset
pip install -r requirements.txt
python scripts/scrape_toolify.py
