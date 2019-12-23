# Breast-Cancer-Prediction
Using Machine Learning to predict if the cancer diagnosis is benign or malignant based on several observations/features.
30 features are used, examples:

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

Datasets are linearly separable using all 30 input features

Algorithm used: Support Vector Machine (with optimization and scaling, as needed)

Number of Instances: 569
Class Distribution: 212 Malignant, 357 Benign
Target class:
   - Malignant
   - Benign
