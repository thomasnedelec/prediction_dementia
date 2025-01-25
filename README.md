# Machine Learning Algorithms for Predicting Neurodegenerative Disease Risk  

## Overview  
This repository contains the implementation of machine learning algorithms described in the manuscript:  
**"Machine learning prediction algorithms for 2-, 5-, and 10-year risk of Alzheimer’s, Parkinson’s, and dementia at age 65: a study using medical records from France and the UK General Practitioners."**  

The study focuses on leveraging electronic health records (EHR) to develop risk prediction algorithms for Alzheimer’s disease (AD), Parkinson’s disease (PD), and dementia. The goal is to enable early detection at age 65 using routinely collected healthcare data, such as medications, comorbidities, and demographic factors.  

## Key Features  
- **Data sources**:  
  - UK General Practitioner records  
- **Population**:  
  - Cohort of 76,427 individuals, all aged 65 at baseline  
- **Prediction targets**:  
  - 2-year, 5-year, and 10-year risk for dementia, AD, and PD  
- **Model performance**:  
  - Achieved a 38.4% detection rate for dementia (2 years) with a 5% false-positive rate.  
- **Validation**:  
  - Tested across datasets from France and the UK for cross-country generalizability.  

## Requirements  
- Python 3.8+  
- Required Python libraries:  
  - scikit-learn  
  - xgboost  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  

## Contributors  
- **Karim Zaidi**  
- **Charlotte Montaud**  
  *Interns at ICM (2023-2024)*  
- **Supervisors**:  
  - Thomas Nedelec  
  - Octave Guinebretiere  

## Citation  
If you use this code, please cite the manuscript:  
> Nedelec T., Zaidi K., Montaud C.,Guinebretiere O. et al *Machine learning prediction algorithms for 2-, 5-, and 10-year risk of Alzheimer’s, Parkinson’s, and dementia at age 65: a study using medical records from France and the UK General Practitioners* (2025). 

## License  
This repository is licensed under the MIT License. 
