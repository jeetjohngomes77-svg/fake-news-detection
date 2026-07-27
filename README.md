# Fake News Detection Using Machine Learning
### IDEAS TIH Summer Internship 2026 — Section 2
### Indian Statistical Institute, Kolkata

## Project Overview
This project builds a fake news detection system using 
classical machine learning techniques to classify news 
articles as real or fake based on their text content.

## Dataset
Fake and Real News Dataset from Kaggle by Clement Bisaillon
- 44,898 total articles (before cleaning)
- 38,646 articles (after removing duplicates)
- True.csv: Real news from Reuters
- Fake.csv: Fake news from unreliable sources

## Models Used
- Logistic Regression
- Naive Bayes
- Decision Tree Classifier

## Results Summary
| Model | Best Accuracy | Precision |
|---|---|---|
| Logistic Regression | 98.93% | 99% |
| Naive Bayes | 94.46% | 94% |
| Decision Tree | 99.34% | 99% |

## Key Finding
All three models were tested across 7 train-test splits 
from 80/20 to 50/50. None of the models showed a true 
breaking point within the tested range. Naive Bayes was 
the first to show signs of breaking with a precision 
drop at 50/50.

## Tools and Libraries
- Python
- Google Colab
- pandas
- scikit-learn
- matplotlib
- seaborn
- Kaggle API

## Repository Contents
- Fake_News_Detection.ipynb: Complete Colab notebook
- Fake_News_Detection_Report.docx: Project report
- README.md: Project overview

## Mentor
Dr. Dipashree Pal
IDEAS TIH, ISI Kolkata
