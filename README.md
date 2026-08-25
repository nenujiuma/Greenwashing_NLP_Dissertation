# Greenwashing Risk Indicators in UK Fashion Retail Sustainability Disclosures

This repository contains the Python notebook, derived datasets, statistical outputs and visualisations for a dissertation project on greenwashing-risk indicators in UK fashion retail sustainability disclosures.

The project uses Natural Language Processing (NLP) to examine whether selected UK fashion retailers' sustainability disclosures show highly positive language or selective ESG topic coverage when compared with company-disclosed environmental indicators.

## Companies Analysed

- ASOS plc
- Boohoo Group plc
- Marks and Spencer Group plc
- Next plc
- JD Sports Fashion plc

The study covers annual reports from 2019 to 2024.

## Methods Used

- PDF text extraction and cleaning
- VADER sentiment analysis
- BERTopic topic modelling
- Manual ESG/environmental indicator extraction
- Descriptive statistics
- Correlation analysis
- Exploratory linear regression
- Mann-Whitney U test
- Data visualisation

## Important Data Note

Raw annual report PDFs and full extracted text files are not included in this repository due to copyright restrictions. Source report URLs are provided in the report collection tracker, while derived datasets, redacted outputs and analysis results are included for reproducibility.

The ESG indicators used in this project are company-disclosed quantitative environmental indicators extracted from annual reports. They are not independent third-party ESG ratings. Therefore, findings should be interpreted as exploratory greenwashing-risk indicators and disclosure-performance misalignment signals, not as proof of greenwashing.

## Repository Structure

- `greenwashing_analysis_final.ipynb` – main Python notebook
- `data/` – final datasets and source tracker
- `bertopic_outputs/` – BERTopic outputs and redacted topic files
- `results/` – statistical outputs and summary findings
- `figures/` – final visualisations

## How to Run

Install the required Python packages listed in `requirements.txt`, then open and run:

`greenwashing_analysis_final.ipynb`

## Author

MSc Business Analytics Dissertation Project
