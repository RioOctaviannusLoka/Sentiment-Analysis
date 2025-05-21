<h1 align="center">Sentiment Analysis</h1>

---

# Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)

# Project Overview

This Sentiment Analysis project aims to analyze user feedback from Google Play Store reviews of the popular game [Mobile Legends: Bang Bang](https://play.google.com/store/apps/details?id=com.mobile.legends&hl=id). By processing and classifying the reviews, this project provides insights into user satisfaction, common complaints, and overall sentiment trends related to the game.

The main objectives of this project are:
- To collect and preprocess user review data from the Google Play Store using google play scraper
- To perform sentiment analysis to classify reviews into positive, negative, or neutral categories.
- Using 4 different schemas to compare each schemas performance on sentiment analysis

# Project Structure

```
├── Analisis_Sentimen.ipynb       # main notebook for sentiment analysis
├── Data_Scraping.ipynb           # notebook for data scraping with google play scraper
├── dataset.csv                   # raw dataset of user reviews
├── README.md                     # project documentation
└── requirements.txt              # list of dependencies
```

# Tech Stack

<a href="https://www.python.org/"><img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python Icon" title="Python" width="65" height="65" /></a>
<a href="https://jupyter.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=jupyter" alt="Jupyter Notebook Icon" title="Jupyter Notebook" width="65" height="65" /></a>
<a href="https://pandas.pydata.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=pandas" alt="Pandas Icon" title="Pandas" width="65" height="65" /></a>
<a href="https://scikit-learn.org/stable/"><img src="https://go-skill-icons.vercel.app/api/icons?i=scikitlearn" alt="Scikit Learn" title="Scikit Learn" width="65" height="65"/></a>
<a href="https://keras.io/"><img src="https://skills.syvixor.com/api/icons?i=keras" alt="Keras" title="Keras" width="65" height="65"/></a>

# Installation

1. Clone this repository

   ```bash
   git clone https://github.com/RioOctaviannusLoka/Sentiment-Analysis.git
   ```

2. Install Python Virtual Environment Library

   ```bash
   pip install virtualenv
   ```

3. Create Python Virtual Environment

   Linux / Mac:

   ```bash
   python3 -m virtualenv venv
   ```

   Windows:

   ```bash
   python -m virtualenv venv
   ```

4. Activate the Environment

   Linux / Mac:

   ```bash
   source venv\bin\activate
   ```

   Windows:

   ```bash
   venv\Scripts\activate
   ```

5. Install all the requirements

   ```bash
   pip install -r requirements.txt
   ```

# Usage
1. Activate the Environment

   Linux / Mac:

   ```bash
   source venv\bin\activate
   ```

   Windows:

   ```bash
   venv\Scripts\activate
   ```

2. Open Data Scraping notebook, then run each cell codes

3. Open Sentiment Analysis notebook, then run each cell codes

4. Exit the Virtual Environment

   ```bash
   deactivate
   ```

---

Copyright &copy; 2025 - Rio Octaviannus Loka