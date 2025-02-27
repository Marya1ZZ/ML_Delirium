# ML to Predict Delirium
Datathon Course Project  
This repository contains scripts, documentation, and partial datasets for a delirium prediction project focusing on patients in palliative care. The main objective is to investigate risk factors and develop machine learning models to identify delirium cases early.

# Repository Structure
scripts/
Contains multiple script files (Python notebooks, R scripts, etc.) used for data preprocessing, exploratory data analysis (EDA), and machine learning modeling.

data/
Includes non-sensitive subsets of data, such as model performance summaries, diagnosis maps (ICD mappings), and any relevant intermediate outputs. The large MIMIC data is not stored here due to privacy/size constraints.

docs/
Holds the final report(s) in PDF/Word format and any supporting documentation or presentation slides.

README.md
This file, providing a quick overview of the project, instructions to reproduce key steps (minus the private MIMIC data), and references to scripts/folders.

# How to Use
Review theinterim reports in docs/ for a summary of our methods (including missing data strategies) and key modeling results.
Explore the scripts in scripts/ to see the workflow for data cleaning, feature engineering, and various machine learning approaches (e.g., SMOTE oversampling, class-weight adjustments).
Check the data/ folder for partial or synthetic data examples, model performance tables, and ICD code mappings.
Note: Full MIMIC data is excluded due to size and confidentiality.
Contact: If you need additional information on replicating the analysis (particularly merging with MIMIC-IV), please consult the project’s documentation or contact the maintainers.
# Notes
MIMIC Data: Not included here for privacy and size reasons; the processing scripts assume an existing structure of MIMIC files.
Dependencies: Most scripts rely on Python 3.8+ with common libraries like pandas, scikit-learn, xgboost, and numpy. Check individual scripts or notebooks for detailed requirements.
License: MIT License
