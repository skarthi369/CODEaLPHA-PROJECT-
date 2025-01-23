project 1
# A/B Testing for Marketing Campaign Optimization

This project analyzes the performance of two marketing campaigns, a control campaign and a test campaign, using A/B testing methodology. The goal is to determine if the test campaign leads to statistically significant improvements in key performance indicators (KPIs) compared to the control campaign. 

## Data

The project utilizes two datasets containing information on campaign performance metrics such as impressions, clicks, purchases, and spend. The data is processed and cleaned using Python libraries like Pandas and NumPy.

## Methodology

1. **Data Exploration and Visualization:** The data is explored using descriptive statistics and visualizations such as KDE plots and box plots to understand the distributions of key metrics and identify potential outliers.

2. **KPI Calculation:** Relevant KPIs such as Click-Through Rate (CTR), Conversion Rate (CR), Cost-Per-Click (CPC), and Cost-Per-Acquisition (CPA) are calculated to evaluate campaign effectiveness.

3. **Statistical Testing:** The Mann-Whitney U test is applied to compare the distributions of KPIs between the control and test campaigns. This non-parametric test is used due to the non-normality of the data.

4. **Results and Insights:** The results of the statistical tests are interpreted to identify any significant differences in campaign performance. These insights provide recommendations for campaign optimization.

## Tools and Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Pingouin, Statsmodels, Google Colab.

## Outcome

The project aims to determine whether the test campaign is more effective than the control campaign based on the chosen KPIs. It provides data-driven insights for improving marketing strategies and maximizing return on investment.


project  2

# Boston Housing Price Prediction

This project uses a simple linear regression model to predict housing prices in Boston based on various features.

## Dataset

The dataset used in this project is the Boston Housing dataset, which is a popular dataset for regression tasks. It contains information about various features of houses in Boston, such as the average number of rooms, crime rate, and proximity to employment centers.

## Model

A simple linear regression model is used to predict the median value of owner-occupied homes (MEDV) based on the other features in the dataset. The model is trained using the training set and evaluated using the testing set.

## Evaluation

The model's performance is evaluated using the mean squared error (MSE) and the R-squared value. The MSE measures the average squared difference between the actual and predicted values, while the R-squared value measures the proportion of variance in the target variable that is explained by the model.

## Usage

To run this project, you will need to have Python 3 installed along with the following libraries:

* pandas
* numpy
* matplotlib
* scikit-learn

You can install these libraries using pip:

Once you have installed the necessary libraries, you can run the code in the notebook to train and evaluate the model.

## Results

The model achieves an MSE of `0.29` and an R-squared value of `0.71`. This indicates that the model is able to explain a significant portion of the variance in the target variable.

## Contributing

Contributions to this project are welcome. If you find any issues or have any suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
