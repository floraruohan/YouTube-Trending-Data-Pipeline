# YouTube Trending Data Pipeline

`AI-Assisted Development` · `Python` · `YouTube Data API` · `NLP` · `Data Engineering` · `Platform Analytics`

This project builds a reusable pipeline for collecting, structuring, and analyzing the daily Top 100 most popular YouTube videos in the United States.

Developed as part of my research assistant work at Columbia University, the pipeline supports longitudinal analysis of online content trends using large-scale platform data.

## Project Overview

The pipeline automatically retrieves daily YouTube trending-video metadata through the YouTube Data API, standardizes the data, and converts unstructured text and platform metadata into structured research variables.

The 2025 dataset contains 36,000+ video records collected across daily snapshots, with the pipeline continuing to support daily data collection in 2026.

## AI Collaboration

AI was integrated throughout the development workflow to accelerate code generation, debugging, iteration, and data-processing design.

I defined the research objective, required variables, classification logic, and validation criteria, while using AI to assist with:

- Python code generation and refactoring
- API integration and debugging
- Data-cleaning workflow design
- Classification-rule development and iteration
- Error diagnosis and pipeline optimization

All AI-assisted outputs were reviewed and validated before being incorporated into the final workflow.

## My Role

- Built an AI-assisted Python pipeline for daily U.S. YouTube Top 100 data collection
- Retrieved video, channel, engagement, and content metadata through the YouTube Data API
- Designed text-cleaning and rule-based political-content classification logic
- Created daily political-content share metrics for longitudinal analysis
- Maintained and validated large-scale daily datasets for downstream research

## Data Workflow

**Research Question → AI-Assisted Development → YouTube API → Daily Top 100 → Data Cleaning → Content Classification → Daily Metrics → Research Dataset**

## Repository Structure

```text
youtube-trending-data-pipeline/
│
├── README.md
│
├── notebooks/
│   └── youtube_daily_pipeline.ipynb
│
└── data/
    ├── sample_daily_top100.csv
    └── sample_2025_trending.csv
```
## Dataset

The pipeline captures variables including:
- Video title and description
- Publication date
- Video and channel identifiers
- View counts
- Video duration
- Daily snapshot date
- Political-content classification
- Daily political-content share
A representative sample is included in this repository. The full research dataset is not publicly released.

## Key Takeaway

This project showed how AI-assisted development can accelerate the construction and iteration of reproducible data pipelines while keeping research design, classification logic, and output validation under human control.

It strengthened my experience in combining AI, data engineering, and platform analytics to transform large-scale digital content into structured data for longitudinal research.
