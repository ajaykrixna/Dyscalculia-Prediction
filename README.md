# Dyscalculia Detection Using Machine Learning

This project implements a machine learning model to detect Dyscalculia using cognitive task performance data.

## Dataset
- OpenICPSR Dyscalculia Study Data
- Includes arithmetic accuracy, reaction time, numerosity, symbolic comparison, and working memory features

⚠ Dataset not included due to license restrictions.

## Methodology
- Data merging from multiple cognitive tasks
- Missing value handling and feature scaling
- Random Forest Classifier for prediction

## Results
- Achieved ~90–96% accuracy
- Feature importance analysis highlights reaction time and symbolic processing

## Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Usage
1. Place dataset files in `dataset/`
2. Run `Dyscalculia.ipynb`
3. Trained model saved in `model/`

## Disclaimer
This tool is for screening and academic research only, not a medical diagnosis.
