<h1>Logistic Regression Classification Project</h1>

<p>
This repository contains a complete end-to-end implementation of a Logistic Regression
classification model with proper data preprocessing, feature scaling, model training,
and in-depth performance evaluation.
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
I have worked with the Breast Cancer dataset avaiable at Kaggle, which contains some very detailed measurements of cells. Along with each observation of measurements, it has the diagnosis of the cell (malignant or not). I have trained a model that will be able to predict whether or not a given cell is malignant given only its measurements
The goal of this project is to build a reliable binary classification model and
understand how thresholds affect model performance.
Rather than relying only on accuracy, the project focuses on evaluating real-world
metrics such as recall, false positives, and ROC–AUC.
</p>

<hr>
<hr>

<h2>🧠 Why This Project Is Important</h2>
<p>
This project goes beyond simply training a classification model. It focuses on
<strong>understanding model behavior</strong>, <strong>decision boundaries</strong>,
and <strong>performance trade-offs</strong>, which are critical in real-world
machine learning applications—especially in sensitive domains like healthcare.
</p>

<p>
In medical diagnosis problems such as breast cancer detection, false negatives
(missing a malignant case) can be far more costly than false positives. This project
explicitly analyzes how changing probability thresholds impacts recall and false
positive rates, rather than blindly relying on default predictions.
</p>

<hr>

<h2>📊 Analytical Thinking:</h2>
<ul>
  <li>Moves beyond accuracy to evaluate ROC–AUC, recall, and false positive rate</li>
  <li>Uses probability outputs instead of hard labels to understand model confidence</li>
  <li>Performs threshold sensitivity analysis to study decision trade-offs</li>
  <li>Interprets results in a domain-aware manner (healthcare risk considerations)</li>
  <li>Focuses on explainability and interpretability of model decisions</li>
</ul>

<hr>

<h2>🔬 Real-World Relevance</h2>
<p>
Logistic Regression is widely used in medical, financial, and risk-based systems
because of its interpretability. This project demonstrates how such models can be
evaluated responsibly by examining how decisions change with varying thresholds,
making it suitable for deployment scenarios where human oversight is required.
</p>


<h2>🛠️ Libs and Tech:</h2>
<ul>
  <li>Python</li>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>Matplotlib</li>
  <li>Scikit-learn</li>
  <li>Seaborn</li>
</ul>

<hr>

<h2>📊 Workflow</h2>
<ul>
  <li>Data loading and inspection</li>
  <li>Data cleaning,Label encoding and categorical handling</li>
  <li>Feature normalization using StandardScaler</li>
  <li>Train–test split for unbiased evaluation</li>
  <li>Model training using Logistic Regression</li>
  <li>Probability-based predictions,ROC-AUC,threshold variation table</li>
</ul>

<hr>

<h2>📈 Model Evaluation</h2>
<ul>
  <li>Confusion Matrix analysis</li>
  <li>ROC (Receiver Operating Characteristic) Curve visualization</li>
  <li>AUC (Area Under Curve) score computation</li>
  <li>Threshold analysis from 0 to 1 (step size = 0.05)</li>
  <li>TPR (Recall) and FPR trade-off table</li>
</ul>

<hr>

<h2>🎯 Threshold Optimization</h2>
<p>
Instead of using a fixed threshold blindly, this project evaluates multiple threshold
values to understand their impact on recall and false positive rate.
A threshold of <strong>0.50</strong> is selected as it provides a balanced trade-off and
serves as the default decision boundary for Logistic Regression.
</p>

<hr>

<h2>🚀 Key Learnings</h2>
<ul>
  <li>Why feature scaling is essential for optimization-based models</li>
  <li>How Logistic Regression uses the sigmoid function to estimate probabilities</li>
  <li>Why ROC–AUC is more informative than accuracy for imbalanced data</li>
  <li>How threshold tuning impacts real-world decision making</li>
</ul>

<hr>

<h2>📂 Repository Structure</h2>
<pre>
├── final_project_logisticRegression.ipynb
├── data.csv
</pre>

<hr>

<h2>📌 Conclusion</h2>
<p>
This project demonstrates not just model building, but also thoughtful evaluation
and interpretability. It reflects a production-oriented mindset by analyzing
probabilities, thresholds, and trade-offs
</p>

<hr>

<h2>🙌 Acknowledgements</h2>
<p>
 Kaggle(for the dataset):https://www.kaggle.com/code/alexandreao/logistic-regression-0-98-acc-on-breast-cancer/notebook?scriptVersionId=123698399
</p>
