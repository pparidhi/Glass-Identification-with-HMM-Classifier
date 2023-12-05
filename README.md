# Glass Identification with HMM Classifier

## Overview

This project employs a Hidden Markov Model (HMM) classifier to classify types of glass based on the Glass Identification dataset from the UCI Machine Learning Repository. The classification of glass types has significance in criminological investigations, where correctly identifying glass left at a crime scene can serve as crucial evidence.

## Dataset

The dataset can be accessed (https://archive.ics.uci.edu/ml/datasets/Glass+Identification). 
It consists of continuous attributes related to the chemical composition of glass, including refractive index, sodium, magnesium, aluminum, silicon, potassium, calcium, barium, and iron. The last column serves as the class identifier (1-7).

### Attribute Information
1. Id number: 1 to 214 (do not use for classification)
2. RI: refractive index
3. Na: Sodium (unit measurement: weight percent in corresponding oxide)
4. Mg: Magnesium
5. Al: Aluminum
6. Si: Silicon
7. K: Potassium
8. Ca: Calcium
9. Ba: Barium
10. Fe: Iron

### Class Descriptions
1. building_windows_float_processed
2. building_windows_non_float_processed
3. vehicle_windows_float_processed
4. vehicle_windows_non_float_processed (none in this database)
5. containers
6. tableware
7. headlamps

## Evaluation Metrics

The classification performance of the HMM classifier is assessed using 5-fold cross-validation. The following evaluation metrics are provided:

1. Confusion Matrix
2. Sensitivity
3. Specificity
4. Total Accuracy
5. F1-Score
6. ROC Curve
7. Area Under Curve (AUC)

## Dependencies

- Python 3.x
- NumPy
- Scikit-learn
- Matplotlib
