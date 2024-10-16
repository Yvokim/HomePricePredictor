 California Housing Price Prediction

### Overview
This project focuses on predicting housing prices in California using various features such as median income, house age, and geographic location. The model built for this task is a Random Forest Regressor, which was fine-tuned using GridSearchCV for optimal performance.

### Project Structure

- California_Housing_Project.ipynb: Jupyter Notebooks with the dataset and process used for data analysis, model training, and evaluation.


### Getting Started
To get started with this project, clone the repository and install the necessary dependencies.

#### Prerequisites
- Python 3.x
- Libraries: `scikit-learn`, `pandas`, `numpy`, `matplotlib`

#### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Yvokim/HomePricePredictor.git
   cd HomePricePredictor
   ```
2. Install required libraries as shared above
   

### Data
The dataset used in this project comes from the California Housing dataset, which includes information about housing features like median income, house age, and more. The dataset is preprocessed, and features were scaled before feeding them into the model.

### Models
The project explores multiple models:
1. **Linear Regression**: Baseline model to predict house prices.
2. **Decision Tree Regressor**: Tree-based model to explore patterns in the data.
3. **Random Forest Regressor**: The final model, optimized using GridSearchCV.



### Results
After training and tuning, the Random Forest Regressor model produced the following performance metrics:
- **Mean Squared Error (MSE)**: 0.2548
- **Root Mean Squared Error (RMSE)**: 0.5048
- **R2 Score**: 0.8056

### Usage
Once the model is saved(.joblib), you can use it to predict house prices based on new input data:


### Visualizations
Feature importance is visualized to understand which factors most influence house prices:
- Median income is the most important factor, followed by average occupancy and geographical location.

### Contributing
If you wish to contribute, feel free to fork the repository and submit a pull request.

### License
This project is licensed under the MIT License.

