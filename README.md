# Machine_Failure_prediction
Predicting machine failures using logistic regression based on sensor data.
### Table of contents
<ul>
 <li>Introduction</li>
 <li>Dataset</li>
 <li>Exploratory Data Analysis(EDA)</li>
 <li>Model Implementation</li>
 <li>Evaluation Metrics & Results</li>
 <li>Visualization</li>
</ul>

### Introduction
This project aims to predict machine failures using logistic regression, helping to prevent unexpected downtime in industrial environments.
### Dataset
<ul>
 <li>The dataset contains machine sensor readings like temperature, pressure, volatile organic compound (VOC)level, current sensor readings etc.
 with each record labeled as <b>failure(1) or no failure(0)</b></li>
 <li><b>Source : </b>Teachnook (online course project)</li>
</ul>

### Exploratory Data Analysis(EDA)
<b>Checked for null values - </b> No missing data detected.
<b>Checked feature correlation - </b> Identified relationships between sensor readings.
<b>Assigned dependent & independent variables - </b>Selected X features for model training.
### Model Impelementation
<ul>
 <li><b>Algorithm Used : </b>Logistic Regression.</li>
 <li><b>Steps Taken : 
 <ol>
  <li>Splitting the dataset into training and testing sets.</li>
  <li>training the logistic regression model.</li>
  <li>Predicting machine failure probabilities.</li>
 </ol>
 </li>
</ul>
  
### Evaluation Metrics & Results
The model's performance was evaluated using:
<ul>
 <li>Accuracy : 91%</li>
</ul>

### Visualizations
<ul>
 <li><b>Feature Correlation Bar Graph - </b>To visualize the correlation of dependent features with respect to independent feature.</li>
 <li><b>Confussion Matrix Heatmap - </b>Shows the model's performance in clessifying failures vs. non-failures.</li>
</ul>
