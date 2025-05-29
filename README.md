# Advanced Analytics in Business – Group Assignments Repository

This repository contains the collective work of our team for the Advanced Analytics in Business course at the KU Leuven for Summer Semester 2025. The repository is structured into four main assignment folders, each containing final code, exploratory work, and assets.

## Team Members
- Ashutosh Jha  
- Diederik Symons  
- Guus Spitters  
- Orsolya Paróczi  
- Zsombor Várkonyi  

## Directory Structure

```
ADV_ANALYTICS_BUSINESS/
│
├── as1/                      # Assignment 1: Real Estate Price Prediction
│   ├── assets/               # Visual assets and plots
│   ├── code/                 # Final notebooks and submission files
│   │   ├── final_model_predict_to_submit.ipynb
│   │   ├── final_model_train.ipynb
│   │   └── submission3.csv
│   ├── data/                 # Input data files
│   └── exp/                  # Experimental and intermediate notebooks
│
├── as2/                      # Assignment 2: Country Classification via Street View Images
│   ├── code/
│   │   ├── AAB_ASS2_blackouts_cleaned.ipynb
│   │   └── AAB_ASS2_final_model_blurred.ipynb
│   ├── data/
│   └── exp/
│
├── as3/                      # Assignment 3: LLM-based Text Classification (arXiv Tags)
│   ├── assets/
│   ├── code/
│   │   └── stream_analytics.ipynb
│   ├── exp/
│   └── outputs/
│
├── as4/                      # Assignment 4: Graph Analytics on Steam Social Network
│   ├── assets/
│   ├── code/
│   └── exp/
│
├── requirements.txt          # Python dependencies
└── README.md                 # Repository overview (this file)
```

## Assignments

### Assignment 1: Real Estate Price Prediction
Focus on tabular data preprocessing, feature engineering, ensemble modeling, and interpretability via SHAP.  
Final notebook: `as1/code/final_model_predict_to_submit.ipynb`

### Assignment 2: Image Classification
Geolocation using fine-tuned CNNs (MobileNetV2, EfficientNetB1) on panoramic Street View imagery, enhanced with data augmentation and interpretability (XRAI).  
Final notebook: `as2/code/AAB_ASS2_final_model_blurred.ipynb`

### Assignment 3: Tag Prediction using LLMs
Live-streaming classification of arXiv papers using Google’s Gemini API and a custom performance metric.  
Final notebook: `as3/code/stream_analytics.ipynb`

### Assignment 4: Graph Analytics
Analysis of "backlog" user behavior in the Steam social network via community detection, centrality measures, and hypothesis testing.  
Final notebook: `as4/code/` (WIP)

## Setup Instructions

```bash
git clone https://github.com/your-team/adv_analytics_business.git
cd adv_analytics_business
pip install -r requirements.txt
```

## Contact

For questions or contributions, feel free to reach out to any team member.
