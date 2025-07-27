# Machine-Learning-Project-Medical-Cost-Insurance
### About
Imagine you work at a health insurance company. Every day, people apply for insurance coverage, and your job is to estimate how much their medical expenses might cost. But there's a problem—people are different. Some are older, some have more kids, some smoke, some live in different regions, and all of these factors affect healthcare costs. How do you fairly and accurately calculate what someone should pay for insurance? That’s where this dataset comes in. It contains real-world examples of people with details like age, BMI, smoker status, and what they were charged for insurance. The goal is to use this data to build a system that can learn from patterns and predict insurance costs for new customers—even those the company hasn’t seen before. <br>
### Problem Statement
Build a machine learning system that predicts the medical insurance cost of a person based on personal, lifestyle, and demographic information.

### Dataset
[Medical Cost insurance From Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)
#### Features
- Age <br>
- Gender <br>
- BMI (Body Mass Index)<br>
- Number of children<br>
- Smoking status<br>
- Residential region<br>
- Output: Estimated insurance charge (in dollars)<br>

### METHODOLOGY
* Normalization: Applied feature normalization to accelerate the gradient descent process and ensure efficient model training. <br>
* Compute Cost: Computed the cost to see how far my prediction is from my actual target value<br>
* Gradient Descent: Implemented linear regression from scratch utilizing gradient descent to predict the Medical Charges by customers based on the given features.<br>
* Evaluation Metric: Utilized the R-squared (r2_score) metric to assess the accuracy of the model's predictions.<br>
* Visualization: Employed various plots and visualizations to gain insights into the data distribution, relationships between features, and the performance of the linear regression model.<br>

### Usage
To Use this project: [Open in Jupyter Notebook](http://localhost:8888/notebooks/Medical%20Cost.ipynb) <br>
Explore the generated plots and visualizations to analyze the data and model performance. <br>
Experiment with different parameters and features to further enhance the model's accuracy.

### Dependencies
- Pandas<br>
- Seaborn<br>
- NumPy<br>
- Matplotlib <br>
- Sklearn<br>
- Train_Test_Split<br>
- OneHotEncoder<br>
- Metrics<br>
- StandardScaler<br>
