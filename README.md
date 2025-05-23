# WineRed-Classification
In this project, I built and compared classification models to predict wine quality using the Wine Red dataset from the UCI Machine Learning Repository. The original quality scores (0–10) were transformed into binary classes based on the average value, separating wines into "below average" and "above average" quality groups.

Key Insight:
K-Nearest Neighbors (KNN) with n_neighbors=1 provided the best accuracy among the tested models. All models tended to better identify higher quality wines, highlighting the importance of feature scaling and careful class thresholding to achieve balanced classification performance.
