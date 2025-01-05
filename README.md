# Ice Cream Revenue Prediction

This project predicts the **Revenue** of an ice cream shop based on the **Temperature**. A linear regression model is used to predict the relationship between temperature and revenue, where higher temperatures tend to result in higher ice cream sales.

## Dataset

The dataset contains two columns:

- **Temperature**: The temperature (in Celsius) on a given day.
- **Revenue**: The revenue generated by the ice cream shop on that day.

### Example of Data

| Temperature | Revenue |
|-------------|---------|
| 24.6        | 535     |
| 26.1        | 626     |
| 27.8        | 661     |
| 20.6        | 488     |
| 11.6        | 317     |

## Project Workflow

1. **Data Loading**: The dataset is loaded from a CSV file hosted on GitHub.
2. **Data Preprocessing**: The target variable (`Revenue`) is separated from the feature (`Temperature`). The data is then split into training and testing sets.
3. **Model Training**: A **Linear Regression** model is trained on the training data to predict revenue based on temperature.
4. **Prediction**: The trained model is used to predict the `Revenue` for the test data.
5. **Model Evaluation**: The model is evaluated using the following metrics:
   - **Mean Absolute Error (MAE)**
   - **Mean Absolute Percentage Error (MAPE)**
   - **Mean Squared Error (MSE)**

## Installation

To run this project, you need to have Python installed on your machine along with the required libraries. You can install the necessary libraries using `pip`:

```bash
pip install pandas scikit-learn

**Usage**
Clone the repository to your local machine:
--git clone https://github.com/YBIFoundation/Ice-Cream-Revenue-Prediction.git

****Run the Python script:

--python ice_cream_revenue_prediction.py


**Results**
After training the model, the following evaluation metrics were obtained:
Mean Absolute Error (MAE): 2.44e-14
Mean Absolute Percentage Error (MAPE): 6.59e-17
Mean Squared Error (MSE): 2.08e-27

**Conclusion**
The linear regression model successfully predicts the revenue of an ice cream shop based on temperature. The model performs exceptionally well, with near-zero error values, indicating a strong relationship between temperature and revenue.


**Acknowledgements**
The dataset was sourced from the YBI Foundation.

### Explanation:
- **Dataset Description**: Describes the columns in the dataset.
- **Project Workflow**: Outlines the steps followed in the project.
- **Installation**: Details how to install the required libraries.
- **Usage**: Instructions on how to clone and run the project.
- **Results**: Provides the evaluation metrics obtained after training the model.
- **License and Acknowledgements**: Standard sections for licensing and credits.
