<h1 align="center">Credit Card Approval Prediction</h1>
<p align="center">
  A machine learning project for predicting credit card approvals based on user demographics and financial information.
</p>

<h2>Overview</h2>
<p>
  This project utilizes data analysis and machine learning techniques to predict whether a credit card application will be approved or not. The dataset used contains information on various customer details such as income, employment, family status, etc.
</p>

<h2>Dataset</h2>
<ul>
  <li><b>Source:</b> Kaggle.</li>
  <li><b>Number of Rows:</b> 25,134</li>
  <li><b>Number of Columns:</b> 20</li>
  <li><b>Target Column:</b> Status (Approved/Rejected)</li>
</ul>

<h2>Steps Involved</h2>
<ol>
  <li>Data Cleaning</li>
  <li>Exploratory Data Analysis (EDA)</li>
  <li>Feature Selection</li>
  <li>Data Encoding</li>
  <li>Model Training and Evaluation</li>
</ol>

<h2>Metrics</h2>
<p>Here are the performance metrics for the models evaluated:</p>
<table border="1" style="border-collapse: collapse; text-align: center;">
  <tr>
    <th>Model</th>
    <th>Accuracy</th>
    <th>F1 Score</th>
    <th>Precision</th>
    <th>Recall</th>
    <th>Confusion Matrix</th>
  </tr>
  <tr>
    <td>Random Forest</td>
    <td>98.76%</td>
    <td>98.48%</td>
    <td>98.30%</td>
    <td>98.76%</td>
    <td>[[4726, 13], [46, 6]]</td>
  </tr>
  <tr>
    <td>XGBoost</td>
    <td>98.76%</td>
    <td>98.34%</td>
    <td>97.98%</td>
    <td>98.76%</td>
    <td>[[4731, 8], [51, 1]]</td>
  </tr>
  <tr>
    <td>SVM</td>
    <td>98.91%</td>
    <td>98.37%</td>
    <td>97.84%</td>
    <td>98.91%</td>
    <td>[[4739, 0], [52, 0]]</td>
  </tr>
</table>

<h2>Reason for Choosing Random Forest</h2>
<p>
  Random Forest was chosen as the final model for this project due to its balance between accuracy and interpretability. It achieved an accuracy of 98.76%, with the highest F1 score of 98.48% among all models. Additionally, Random Forest is less prone to overfitting compared to other algorithms and performs well on datasets with categorical and numerical features.
</p>

<h2>Installation</h2>
<pre>
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
</pre>

<h2>Usage</h2>
<p>Run the Jupyter Notebook or Python script to analyze and predict credit card approvals.</p>

<h2>Conclusion</h2>
<p>This project highlights the importance of feature engineering and model selection in building effective predictive models. Random Forest emerged as the most effective model for this dataset due to its superior metrics and robustness.</p>

<h2>Connect with Me</h2>
<p>Feel free to connect with me on <a href="https://linkedin.com/in/tark-patel" target="_blank">LinkedIn</a>.</p>
