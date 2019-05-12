## Objective:
- Predicting if the cancer diagnosis is benign or malignant based on several observations/features.

( Malignant: Malignant means that the tumor is made of cancer cells, and it can invade nearby tissues.

   Benign: Benign means that the tumor does not invade nearby tissue or spread to other parts of the body.)

## Description:
- 30 features are used, examples:
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

- Datasets are linearly separable using all 30 input features
- Number of Instances: 569
- Class Distribution: 212 Malignant, 357 Benign
- Target class:
         - Malignant
         - Benign 

## Dataset:
- https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)
