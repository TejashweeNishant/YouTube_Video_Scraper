# 📊 YouTube Data Scraping and Analysis Project

## 📌 Project Overview
This project focuses on **scraping YouTube channel data** and performing **Exploratory Data Analysis (EDA)** to derive insights from the content performance.  
The workflow is split into **three Jupyter notebooks**, each handling a different stage of the pipeline — from scraping to cleaning to deep analysis.

---

## 📂 Project Structure

1. **`01_youtube_scraping_channel_data.ipynb`**  
   - Scrapes basic video-level data from a YouTube channel.  
   - Data collected includes:
     - Video Title
     - Views
     - Likes
     - Publish Date
     - Video URL

2. **`02_youtube_scraping_with_descriptions.ipynb`**  
   - Extends the scraper to also collect **video descriptions** for deeper analysis.  
   - Data collected includes:
     - All fields from Notebook 1
     - Video Description

3. **`03_data_cleaning_and_eda.ipynb`**  
   - Cleans and preprocesses the scraped dataset.  
   - Performs **Deep EDA** with visualizations:
     - Views & Likes distributions
     - Top performing videos
     - Engagement rate analysis
     - Keyword frequency in video titles
     - Time-series analysis of content performance  
   - Extracts insights and trends from the dataset.

---

## ⚙️ Requirements

Before running the notebooks, install dependencies:

```bash
pip install pandas numpy matplotlib seaborn beautifulsoup4 requests

