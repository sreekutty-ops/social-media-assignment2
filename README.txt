================================================
COSC2671 Social Media and Network Analytics
Assignment 2 — Group PG18
================================================

Team Members:
  Akash                           s4137826
  Asmi Faisel                     s4134240
  Sreelakshmi Thalodil Sunilkumar s4146925

Project Title:
Doctors vs Influencers: 
Mapping Authority, Sentiment and Community in YouTube Health Discourse



================================================
SUBMISSION FILES
================================================

Report_s4146925_PG_Group18.pdf
  → Full project report (max 20 pages)

s4146925_PG_Group_18.ipynb
  → Main analysis notebook containing all code
    for data collection, preprocessing, text
    analysis, and network analysis

Worksheet_s4146925_PG_Group_18.pdf
  → Team project plan, weekly timesheets for
    each member, and individual self-reflection

Access_s4146925_PG_Group_18.txt
  → GitHub repository access details

data_sample.csv
  → Representative 500-row sample of the cleaned
    dataset showing data structure for both NLP
    (comment text) and network analysis (reply_to)
    components. Full dataset has 18,564 rows.

README.txt
  → This file

================================================
GITHUB REPOSITORY CONTENTS
================================================

s4146925_PG_Group18.ipynb     Main analysis notebook
mental_health_cleaned.csv     Full cleaned dataset
data_sample.csv               500-row submission sample
Report_s4146925_PG_Group18.pdf    Final report
Worksheet_s4146925_PG_Group18.pdf Worksheet
README.txt                    This file

================================================
HOW TO RUN THE NOTEBOOK
================================================

Run all cells in order TOP TO BOTTOM.

STEP 1 — SETUP AND IMPORTS
  Install all required packages (see below)
  Set API_KEY = "your_key" to re-run collection
  Leave API_KEY = "" to skip collection

STEP 2 — DATA COLLECTION (OPTIONAL)
  Collects YouTube videos and comments via API

STEP 3 — DATA PREPROCESSING
  Text cleaning, deduplication, tokenisation,
  and video labelling (doctor/influencer/both)

STEP 4 — TEXT ANALYSIS
  - Unigram and bigram frequency analysis
  - VADER sentiment analysis
  - LDA topic modelling (5 topics)
  - Word cloud generation


STEP 5 — NETWORK ANALYSIS
  - Directed reply graph construction (NetworkX)
  - Centrality measures:
      degree, betweenness, eigenvector,
      clustering coefficient
  - Louvain community detection
  - Network visualisations


STEP 6 — DATA SAMPLE EXPORT
  Exports 500-row representative sample


================================================
REQUIRED PACKAGES
================================================

pip install pandas numpy matplotlib seaborn
pip install nltk scikit-learn wordcloud
pip install networkx python-louvain
pip install google-api-python-client
pip install vaderSentiment

Python version: 3.8+


================================================
DATASET INFORMATION
================================================

Raw comments collected:        19,426
After cleaning:                18,780
Duplicates removed:               333
Final dataset for analysis:    18,564
Videos collected:                  89
  Doctor videos:                   50
  Influencer videos:               22
  Both (mixed):                    17

================================================
IMPORTANT NOTES
================================================

- API_KEY is intentionally left empty ("")
  Add your own YouTube Data API v3 key to
  re-run the data collection section only

- No API keys, credentials, or tokens are
  included anywhere in this submission

- All results in the report were produced
  using the full dataset (18,564 rows)

- data_sample.csv (500 rows) is provided
  to demonstrate data structure only and
  was NOT used to produce the report results

- The submitted code is consistent with
  all results, figures, and tables in the
  report

================================================