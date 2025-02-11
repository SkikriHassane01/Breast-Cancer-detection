# [Breast Cancer Detection Project](https://www.kaggle.com/code/hassaneskikri/breast-cancer-detection/notebook)

## Project Overview

This project implements machine learning models for the detection and diagnosis of breast cancer based on comprehensive datasets. Multiple algorithms are evaluated, and the AdaBoost model is selected for its robust performance. Hyperparameter optimization is performed using Optuna to fine-tune the model for optimal results.

### Key Features:
- **Multiple Algorithms**:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Gradient Boosting  
  - AdaBoost  
  - Support Vector Machine  
  - K-Nearest Neighbors
- **Performance Metrics**: Detailed comparison of training and testing accuracies.
- **Hyperparameter Optimization**: Uses Optuna for the AdaBoost model.
- **End-to-End Workflow**: From data ingestion and preprocessing to model evaluation.

## Installation Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SkikriHassane01/Breast-Cancer-detection.git
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Dataset Setup**:
   - Ensure the dataset (`breast-cancer.csv`) is located in the `Data/` directory.


### Model Performance Metrics

| Algorithm              | Train Accuracy | Test Accuracy |
|------------------------|----------------|---------------|
| Logistic Regression    | 0.986813       | 0.973684      |
| Decision Tree          | 1.000000       | 0.938596      |
| Random Forest          | 1.000000       | 0.964912      |
| Gradient Boosting      | 0.989011       | 0.956140      |
| AdaBoost               | 1.000000       | 0.973684      |
| Support Vector Machine | 0.986813       | 0.973684      |
| K-Nearest Neighbors    | 0.973626       | 0.964912      |

### Hyperparameter Optimization

- The project leverages **Optuna** to automatically search for the best hyperparameters for the AdaBoost model, ensuring optimal performance.

## License Information

This project is licensed under the Apach-2.0 license. For more details, refer to the `LICENSE` file.