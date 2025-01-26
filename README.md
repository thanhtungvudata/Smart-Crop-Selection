# Crop Prediction Using Machine Learning

![Alt text](crop_selection_smart_farming.png)

## Project Overview
This project aims to assist farmers in selecting the most suitable crop for their field based on soil nutrient measurements. The dataset used contains information on essential soil nutrients such as nitrogen (N), phosphorus (P), potassium (K), and pH values, to predict the optimal crop for a given set of soil conditions.

## Dataset
**File:** `soil_measures.csv`

**Columns:**
- `N`: Nitrogen content ratio in the soil.
- `P`: Phosphorous content ratio in the soil.
- `K`: Potassium content ratio in the soil.
- `ph`: Soil pH value.
- `crop`: Target variable indicating the optimal crop.

## Objective
The objective of this project is to:
1. Perform exploratory data analysis (EDA) to understand the dataset.
2. Develop multi-class classification models to predict crops based on soil features.
3. Compare the performance of XGBoost and K-Nearest Neighbors (KNN) models.
4. Determine the most important soil features for accurate predictions.
5. Recommend the best model based on marco f1-score and computational efficiency.

## Models Used
The following models were implemented and compared:
1. **XGBoost (Extreme Gradient Boosting):**
   - Pros: High accuracy, handles feature interactions well.
   - Cons: Computationally intensive.
2. **K-Nearest Neighbors (KNN):**
   - Pros: Simplicity, low training time.
   - Cons: Computationally expensive for large datasets during inference.

## Performance Evaluation
Evaluation metrics used in this project include:
- **Macro F1-Score:** To balance precision and recall across all crop classes.
- **Classification Report:** Provides precision, recall, and F1-score for each class.
- **Confusion Matrix:** To analyze model predictions.

## Results
| Model   | Macro F1-Score |
|---------|---------------|
| XGBoost | 0.82          |
| KNN     | 0.78          |

**Conclusion:**
- XGBoost achieved higher accuracy and better generalization.
- KNN is recommended when computational resources are limited, given its comparable performance with lower training cost.

## Steps to Run the Project
1. Install the necessary dependencies.
2. Load the dataset and preprocess the data.
4. Perform exploratory data analysis (EDA) to understand data distributions.
5. Split the data into training and testing sets.
6. Train machine learning models and fine-tune hyperparameters.
7. Evaluate the models using appropriate metrics.
8. Compare model performance and select the best deployment model.

## Key Findings
- **Feature Importance:** Potassium (K) was identified as the most influential soil feature.

## Future Work
1. Incorporate additional soil parameters such as organic matter and moisture levels.
2. Collect more data
3. Implement deep learning models for improved predictions.
4. Explore deployment options using cloud-based platforms for real-time predictions.

## Contact
For further inquiries or collaboration, please contact me at [my email](mailto:tungvutelecom@gmail.com).


