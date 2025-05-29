# Advanced Analytics in Business – Group Assignments Repository

This repository contains the collective work of our team for the Advanced Analytics in Business course at KU Leuven for Summer Semester 2025. The repository is structured into four main assignment folders, each containing final code, exploratory work, and assets.

## Team Members
- Ashutosh Jha  
- Diederik Symons  
- Guus Spitters  
- Orsolya Paróczi  
- Zsombor Várkonyi  

## Directory Structure

```
CLEAN-MAIN/
│
├── as1/                      # Assignment 1: Real Estate Price Prediction
│   ├── assets/
│   ├── code/
│   │   ├── feature_engr/         # Feature engineering notebooks
│   │   ├── final_model/          # Final training and prediction notebooks
│   │   ├── other_model/          # Additional modeling attempts
│   │   └── pre_processing/       # Data cleaning and preparation notebooks
│   └── data/
│
├── as2/                      # Assignment 2: Country Classification via Street View Images
│   ├── code/
│   │   ├── final_model/          # Final CNN model (EfficientNetB1)
│   │   ├── interpretability_analysis/ # XRAI heatmaps and interpretation
│   │   └── pre_processing/       # Image downscaling and augmentation logic
│   └── data/
│
├── as3/                      # Assignment 3: LLM-based Tag Prediction for arXiv Papers
│   ├── assets/
│   ├── code/
│   │   ├── stream_analytics.ipynb
│   │   └── stream_analytics_final_prompt.ipynb  # Final LLM pipeline with prompt engineering
│   └── outputs/
│
├── as4/                      # Assignment 4: Graph Analytics on Steam Network
│   ├── assets/
│   ├── code/
│   └── resources/
│
├── requirements.txt
└── README.md
```

## Assignments

### Assignment 1: Real Estate Price Prediction
Focus on advanced tabular data handling including preprocessing, outlier filtering, external geospatial feature integration, clustering, and ensemble modeling.  
Final notebooks: `as1/code/final_model/`

### Assignment 2: Image Classification
Country inference from panoramic Street View images using EfficientNet-based CNNs, with interpretability from XRAI and custom augmentations including random blur.  
Final notebook: `as2/code/final_model/`

### Assignment 3: Tag Prediction using LLMs
Live-stream processing of arXiv paper metadata using Google Gemini 2.0 API with custom prompt engineering and evaluation metrics.  
Final notebook: `as3/code/stream_analytics_final_prompt.ipynb`

### Assignment 4: Graph Analytics
Ongoing analysis of Steam social network focused on backlog gamers and play patterns using community detection, centrality, and ego network analysis.  
Final notebook: `as4/code/` (Work in progress)

## Setup Instructions

```bash
git clone https://github.com/your-team/adv_analytics_business.git
cd adv_analytics_business
pip install -r requirements.txt
```