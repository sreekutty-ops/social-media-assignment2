# YouTube Health Discussion Analysis

## Project Overview
This project analyses YouTube health-related discussions to compare the influence of licensed medical professionals and wellness influencers. The study integrates Natural Language Processing (NLP) and Social Network Analysis (SNA) to examine user sentiment, topic patterns, and interaction networks.

---

## Research Objective
To investigate whether social network analysis of YouTube comment interactions can identify influential users and communities, and to compare how doctors and influencers differ in terms of network authority and ideological influence.

---

## Project Structure

- s4146925_PG_Group_XX.ipynb → Main notebook (complete analysis)
- data/ → Raw and processed datasets
- figures/ → Graphs and visualisations
- report/ → Final report (PDF)

---

## How to Run the Project

1. Install required libraries:
pip install pandas numpy matplotlib networkx nltk python-louvain scikit-learn wordcloud

2. Open Jupyter Notebook:
jupyter notebook

3. Open and run:
s4146925_PG_Group_XX.ipynb

4. Run all cells (Restart & Run All) to reproduce results.

---

## Methods Used

Data Processing:
- Cleaning and preprocessing of YouTube comments
- Tokenisation using NLTK TweetTokenizer
- Stopword removal and filtering

NLP Analysis:
- Unigram and Bigram frequency analysis
- Sentiment analysis using VADER
- Topic modelling using Latent Dirichlet Allocation (LDA)

Network Analysis:
- Directed graph construction using reply relationships
- Degree, betweenness, and eigenvector centrality
- PageRank analysis
- Louvain community detection
- Network visualisation

---

## Key Findings
- Doctors demonstrate stronger network authority through higher centrality and engagement.
- Influencers exhibit stronger ideological influence through concentrated and repetitive narratives.
- The interaction network is sparse and fragmented, with limited user-to-user communication.
- Communities are small and weakly connected, indicating low cross-group interaction.

---

## Important Notes
- No API keys or private credentials are included.
- All results in the report can be reproduced by running the notebook.
- Dataset is derived from YouTube comments using the YouTube Data API.

---

## Team Members
- Akash (s4137826)
- Asmi Faisel (s4134240)
- Sreelakshmi Thalodil Sunilkumar (s4146925)

---

## Submission Details
This repository supports the assignment submission, including code, data, and reproducible analysis.
