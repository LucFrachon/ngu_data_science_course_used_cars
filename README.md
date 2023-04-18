# Used Cars Price Prediction: A Complete Data Science Prototype
## CS325: Introduction to Data Science, School of IT, NewGiza University
## Fall 2021

Author: Luc Frachon

---

A complete data science prototype built to teach undergrad students in their second year in Computer Science at NewGiza University.

The data comes from Kaggle and contains used car ads scraped from eBay Germany in 2016. Since the original dataset does not seem to be available anymore, I include it in the repo after translation from German to English. I also include the sanitised and split versions of the data, as well as a file matching German postcodes with geographical coordinates, found [here](https://github.com/WZBSocialScienceCenter).  

The eBay data is fairly large, noisy, and contains some ambiguous variables that could be seen as either continuous or categorical. Moreover, it requires a fair amount of domain knowledge to make full sense of.

The included Jupyter notebooks are:
- `week6_Used Cars - Load and Inspect.ipynb`: Data loading and inspection, with some basic sanitisation.
- `week7_Used Cars - EDA.ipynb`: In-depth exploratory data analysis, and initial ideas for feature engineering, including merging geographical data to make sense of postcodes. 
- `week8 - Cleaning and Formatting.ipynb`: A general illustration of different data cleaning methods, with the continuation of our worked example.
- `Used Cars - Full DS Prototype.ipynb`: A full prototype that takes everything we learned in the previous weeks and applies it in modular code that can be re-used when building a product. We build two models to predict used car prices.

Feel free to reuse this content but please attribute it.
