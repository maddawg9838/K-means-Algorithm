# K-means-Algorithm

## Overview
This project implements K-means clustering and showcases some theoretical work in relation to machine learning.

Theoretical Work:
- `CS 4375 Assignment 3 Report.pdf` - Contains all 3 theoretical questions

Coding Work:
- `CS 4375 Assignment 3.ipynb` Implementation of a K-means clustering algorithm to cluster redundant/repeated tweets into the same cluster.
- `README.md` - This README.

Libraries Used:
  - pandas
  - re
  - random
  - pygments.token (Other)

Dataset: **usnewshealth.txt** file from **Health News in Twitter** from UCML:
https://archive.ics.uci.edu/dataset/438/health+news+in+twitter 

Preprocessing Includes:
  1. Removing any word that starts with the symbol @
  2. Removing any hashtage symbols #
  3. Removing any URL
  4. Converting every word to lowercase
  5. Remove the tweet id and timestamp (stored in a dataframe where they are not utilized)

## Instructions
1. Open [Google Colab](https://colab.research.google.com/).
2. Click **File → Upload notebook** and select `CS 4375 Assignment 3.ipynb`.
4. Make sure you are connected to a runtime.
5. Run all cells sequentially. All necessary libraries are already imported and installed within the notebook.
6. The report includes all plots, diagnostics, and interpretations.
