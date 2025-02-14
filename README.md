# Project ReadMe

## Repository Overview
Welcome to our project repository! This file serves as an orientation guide for anyone exploring the repository. It provides information about the software and platform used, the structure of the project folders, and step-by-step instructions for reproducing our results.

## Section 1: Software and Platform

### Software Used
- **Python (Version 3.13)**

### Required Packages
Ensure the following Python packages are installed before running the code:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn` – to import `TfidfVectorizer`
- `nltk` – to import `stopwords`
- `vaderSentiment` – to import `SentimentIntensityAnalyzer`
- `Word2Vec`

To install all dependencies, run the following command:

```bash
pip install -r requirements.txt


Platform
Developed and tested on Windows 10
Compatible with MacOS and Linux


#section 2:Repo-Structure
ProjectFolder/
│-- data/                 # Contains raw and processed datasets
│   │-- reviews.csv       # Main dataset used in analysis
│-- scripts/              # Source code directory
│   │-- MI2_eda.ipynb     # Data preprocessing script
│   │-- MI3.ipynb         # Sentiment analysis script
│-- outputs/              # Outputs and visualizations
│   │-- sentiment_scores.csv # Generated sentiment scores
│   │-- plots/            # Graphical representations
│-- README.md             # Project documentation (this file)
│-- requirements.txt      # List of required dependencies



#Section 3: Reproducing Results
Clone the Repository

git clone https://github.com/MI3_Project1.git
cd MI3_Project1

Install Dependencies
pip install -r requirements.txt

View Results
Sentiment scores will be saved in results/sentiment_scores.csv
Graphs and visualizations will be available in results/plots/


