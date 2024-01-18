# Predictive_Analysis_on_Breast_Cancer_detection_using_Nested_CV

## Overview
This notebook demonstrates a classification task on breast cancer prediction.   
I will use Nested CV for hyperparameter tuning to get the optimized predictive model.  

## Dataset
We fetch a breast cancer dataset from scikit-learn dataset, which is a copy of UCI ML Breast Cancer Wisconsin (Diagnostic) datasets.  
Data source: https://goo.gl/U2Uwz2  

Some dataset characteristics:  
1. Number of Instances: 569  
2. Number of Attributes: 30 numeric, predictive attributes and the class
3. Attribute Information:  
  - radius (mean of distances from center to points on the perimeter)
  - texture (standard deviation of gray-scale values)
  - perimeter
  - area
  - smoothness (local variation in radius lengths)
  - compactness (perimeter^2 / area - 1.0)
  - concavity (severity of concave portions of the contour)
  - concave points (number of concave portions of the contour)
  - symmetry
  - fractal dimension ("coastline approximation" - 1)
  - class:
    - WDBC-Malignant (Y == 0): 212  
    - WDBC-Benign (Y=1): 357  
