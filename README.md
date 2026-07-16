<h1 align="center">
E-Commerce Customer Intelligence Platform
</h1>

<h2 align="center">
Predictive Analytics, Customer Segmentation & NLP Sentiment Analysis
</h2>

<p align="center">
An End-to-End Data Science Platform Transforming Customer Data into Actionable Business Insights
</p>

<hr>


<h2>Executive Overview</h2>

<p>
E-commerce companies collect millions of customer interactions through transactions,
digital behavior, and product reviews. However, customer data alone does not create
business value unless it can be transformed into meaningful insights and predictive
decisions.
</p>


<p>
This project develops an <b>E-Commerce Customer Intelligence Platform</b> that integrates
data engineering, statistical analysis, machine learning, natural language processing,
customer segmentation, and business analytics to understand customer behavior and
support data-driven decision making.
</p>


<p>
The platform addresses three critical business questions:
</p>

<ul>

<li>
<b>Which customers are likely to leave?</b>
<br>
Using machine learning models to predict customer churn risk.
</li>


<li>
<b>Who are the most valuable customer groups?</b>
<br>
Using clustering techniques to identify customer personas and behavioral patterns.
</li>


<li>
<b>What are customers saying about products?</b>
<br>
Using NLP techniques to analyze customer reviews and sentiment.
</li>

</ul>


<p>
The final solution moves beyond traditional reporting by providing predictive insights
that help businesses improve retention strategies, personalize marketing campaigns,
and enhance customer experience.
</p>


<hr>


<h2>Business Problem</h2>


<p>
Modern e-commerce businesses often have large amounts of customer information stored
across different systems:
</p>


<ul>

<li>Customer demographic information</li>
<li>Transaction history</li>
<li>Product preferences</li>
<li>Customer reviews and feedback</li>
<li>Digital engagement behavior</li>

</ul>


<p>
Without an integrated analytics approach, companies face several challenges:
</p>


<ul>

<li>Customers at risk of churn are identified too late</li>

<li>Marketing campaigns are not personalized</li>

<li>Customer feedback is difficult to analyze at scale</li>

<li>Business decisions rely mainly on historical reporting</li>

</ul>


<p>
This project addresses these challenges by creating a unified customer analytics
platform capable of predicting behavior, understanding customer needs, and generating
actionable business recommendations.
</p>



<hr>


<h2>Project Objectives</h2>


<table>

<tr>
<th>Business Objective</th>
<th>Analytical Solution</th>
</tr>


<tr>
<td>
Predict customer churn
</td>

<td>
Develop classification models to identify customers with high churn probability
</td>

</tr>


<tr>

<td>
Understand customer behavior
</td>

<td>
Apply RFM analysis and behavioral feature engineering
</td>

</tr>


<tr>

<td>
Create customer personas
</td>

<td>
Use clustering algorithms to discover meaningful customer segments
</td>

</tr>


<tr>

<td>
Analyze customer opinions
</td>

<td>
Build NLP pipelines for review sentiment classification
</td>

</tr>


<tr>

<td>
Support business decisions
</td>

<td>
Develop SQL analytics layer for customer and revenue insights
</td>

</tr>


</table>



<hr>


<h2>End-to-End Analytics Workflow</h2>


<pre>

Raw Customer Data

        ↓

Data Cleaning & Quality Validation

        ↓

Exploratory Data Analysis

        ↓

Feature Engineering

        ↓

Machine Learning Modeling

        ↓

Customer Segmentation

        ↓

NLP Sentiment Analysis

        ↓

SQL Business Analytics

        ↓

Customer Intelligence Insights

</pre>



<hr>


<h2>Dataset Overview</h2>


<table>


<tr>
<th>Dataset</th>
<th>Description</th>
</tr>


<tr>

<td>
Customer Behavior Dataset
</td>

<td>
5,630 customer records containing demographic,
behavioral, and transaction features
</td>

</tr>


<tr>

<td>
Customer Review Dataset
</td>

<td>
22,641 product reviews used for sentiment analysis
</td>

</tr>


<tr>

<td>
Prediction Target
</td>

<td>
Customer churn classification
</td>

</tr>


</table>



<hr>


<h2>Data Engineering & Feature Engineering</h2>


<p>
A complete data preparation pipeline was developed to transform raw customer data
into reliable analytical datasets.
</p>


<h3>Data Processing</h3>


<ul>

<li>Missing value treatment</li>

<li>Duplicate validation</li>

<li>Outlier detection</li>

<li>Categorical variable encoding</li>

<li>Feature scaling and normalization</li>

<li>Data quality checks</li>

</ul>



<h3>Behavioral Feature Engineering</h3>


<p>
Customer behavior was transformed into meaningful predictive indicators using:
</p>


<ul>

<li>
<b>RFM Analysis</b>
<br>
Recency, Frequency, and Monetary Value analysis
</li>


<li>
Customer engagement metrics
</li>


<li>
Average order value
</li>


<li>
Purchase frequency indicators
</li>


<li>
Customer lifetime behavior indicators
</li>


</ul>


<p align="center">
<img src="assets/data_quality.png" width="800">
</p>



<hr>


<h2>Exploratory Data Analysis</h2>


<h3>Customer Churn Analysis</h3>


<p align="center">
<img src="assets/churn_distribution.png" width="700">
</p>


<p>
The analysis identified significant behavioral differences between retained and
churned customers. Customer inactivity, complaints, and purchasing behavior were
among the strongest signals associated with churn risk.
</p>



<h3>Purchase Recency Analysis</h3>


<p align="center">
<img src="assets/recency_churn.png" width="800">
</p>


<p>
Customers with longer periods since their last purchase showed increased churn
probability, highlighting recency as an important early warning indicator.
</p>



<hr>


<h2>Customer Churn Prediction</h2>


<h3>Machine Learning Models Evaluated</h3>


<table>

<tr>
<th>Model</th>
<th>Purpose</th>
</tr>


<tr>
<td>Logistic Regression</td>
<td>Baseline interpretable classification model</td>
</tr>


<tr>
<td>Random Forest</td>
<td>Ensemble learning and feature importance analysis</td>
</tr>


<tr>
<td>XGBoost</td>
<td>Advanced gradient boosting classification</td>
</tr>


<tr>
<td>Gradient Boosting</td>
<td>Sequential model optimization</td>
</tr>


<tr>
<td>SVM / KNN</td>
<td>Alternative classification approaches</td>
</tr>


</table>



<h3>Handling Class Imbalance</h3>


<p>
Since churn customers represented only a minority of the dataset, imbalance handling
was required to improve model performance.
</p>


<ul>

<li>SMOTE</li>

<li>Tomek Links</li>

<li>SMOTE-Tomek</li>

<li>Cross-validation optimization</li>

</ul>



<p align="center">
<img src="assets/model_comparison.png" width="900">
</p>



<h3>Final Model Performance</h3>


<table>


<tr>
<th>Metric</th>
<th>Performance</th>
</tr>


<tr>
<td>Accuracy</td>
<td>97%</td>
</tr>


<tr>
<td>Precision</td>
<td>97%</td>
</tr>


<tr>
<td>Recall</td>
<td>97%</td>
</tr>


<tr>
<td>F1 Score</td>
<td>97%</td>
</tr>


<tr>
<td>ROC-AUC</td>
<td>96%+</td>
</tr>


</table>



<hr>


<h2>Explainable Machine Learning</h2>


<p align="center">
<img src="assets/shap_summary.png" width="800">
</p>


<p>
SHAP analysis was applied to understand the factors influencing churn predictions.
The analysis identified:
</p>


<ul>

<li>Customer tenure</li>

<li>Customer complaints</li>

<li>Purchase recency</li>

<li>Product category preferences</li>

<li>Customer engagement behavior</li>

</ul>


<p>
This explainability layer helps translate machine learning predictions into practical
business actions.
</p>



<hr>


<h2>Deep Learning Approach: Artificial Neural Network (ANN) for Churn Prediction</h2>

<p>
To evaluate deep learning performance for customer churn prediction, an Artificial
Neural Network (ANN) model was developed and compared with traditional machine
learning approaches.
</p>

<p>
The objective was to investigate whether neural networks could capture complex
nonlinear relationships in customer behavior data and improve identification of
high-risk customers.
</p>


<h3>Data Preparation & Model Development</h3>

<p>
A complete preprocessing pipeline was implemented before ANN training, including:
</p>

<ul>

<li>Missing value treatment and data validation</li>

<li>Categorical feature encoding</li>

<li>Numerical feature scaling</li>

<li>Feature preparation and selection</li>

<li>Class imbalance handling using SMOTE, Tomek Links, and SMOTE-Tomek</li>

</ul>


<p align="center">
<img src="assets/ann_imbalance_comparison.png" width="850">
</p>



<h3>ANN Architecture</h3>

<p>
Two neural network architectures were developed to evaluate the impact of model
complexity on churn prediction:
</p>


<table>

<tr>
<th>Model</th>
<th>Architecture</th>
<th>Purpose</th>
</tr>

<tr>
<td>ANN Model 1</td>
<td>128-32 neurons</td>
<td>Baseline neural network model</td>
</tr>

<tr>
<td>ANN Model 2</td>
<td>128-64-32 neurons</td>
<td>Capture deeper nonlinear customer patterns</td>
</tr>

</table>


<h3>Optimization Techniques</h3>

<ul>

<li>ReLU activation for nonlinear feature learning</li>

<li>Sigmoid output layer for churn probability prediction</li>

<li>Dropout and L2 regularization to reduce overfitting</li>

<li>Batch normalization for training stability</li>

<li>Early stopping for improved generalization</li>

</ul>


<p align="center">
<img src="assets/ann_architecture.png" width="800">
</p>



<h3>Model Evaluation</h3>


<table>

<tr>
<th>Model</th>
<th>Accuracy</th>
<th>ROC-AUC</th>
<th>Observation</th>
</tr>


<tr>
<td>ANN Model 1</td>
<td>~49%</td>
<td>~49%</td>
<td>Baseline deep learning performance</td>
</tr>


<tr>
<td>ANN Model 2</td>
<td>~51%</td>
<td>~51%</td>
<td>Captured nonlinear patterns but limited improvement</td>
</tr>


</table>


<p>
The ANN models successfully demonstrated neural network development and
optimization; however, ensemble machine learning models such as Random Forest and
XGBoost achieved better performance for this structured customer dataset.
</p>


<p>
This analysis highlights the importance of selecting models based on data
characteristics, interpretability, and business objectives rather than algorithm
complexity alone.
</p>

<hr>
<h2>Customer Segmentation</h2>


<p>
Customer segmentation was performed to discover hidden behavioral patterns and
create actionable customer personas.
</p>


<h3>Methods</h3>


<ul>

<li>K-Means Clustering</li>

<li>DBSCAN Clustering</li>

<li>Cluster validation using Elbow Method and Silhouette Score</li>

</ul>



<p align="center">
<img src="assets/customer_clusters.png" width="800">
</p>



<table>

<tr>
<th>Customer Segment</th>
<th>Business Strategy</th>
</tr>


<tr>
<td>Premium Customers</td>
<td>VIP services and loyalty programs</td>
</tr>


<tr>
<td>Loyal Customers</td>
<td>Personalized recommendations and rewards</td>
</tr>


<tr>
<td>At-Risk Customers</td>
<td>Retention campaigns and targeted incentives</td>
</tr>


<tr>
<td>Inactive Customers</td>
<td>Customer reactivation strategies</td>
</tr>


</table>



<hr>


<h2>NLP Sentiment Analysis</h2>


<p>
Customer reviews contain valuable information about satisfaction, product quality,
and customer experience. NLP techniques were applied to transform unstructured
text into measurable insights.
</p>


<h3>NLP Pipeline</h3>


<pre>

Customer Reviews

        ↓

Text Cleaning

        ↓

Tokenization

        ↓

TF-IDF / Word Embeddings

        ↓

Machine Learning & Deep Learning Models

        ↓

Sentiment Classification

</pre>



<h3>Models Developed</h3>


<ul>

<li>Logistic Regression + TF-IDF</li>

<li>Random Forest + TF-IDF</li>

<li>GRU Deep Learning Model</li>

<li>BERT Transformer Model</li>

</ul>



<p align="center">
<img src="assets/bert_results.png" width="800">
</p>


<p>
The final NLP model achieved more than <b>91% accuracy</b>, enabling automated analysis
of customer feedback and product satisfaction trends.
</p>



<hr>


<h2>SQL Analytics Layer</h2>


<p>
A relational analytics layer was developed using SQLite to provide business users
with direct access to customer and revenue insights.
</p>


<ul>

<li>Revenue analysis</li>

<li>Customer ranking</li>

<li>Product performance analysis</li>

<li>Customer behavior analysis</li>

<li>Business KPI reporting</li>

</ul>



<hr>


<h2>Business Impact</h2>


<ul>

<li>
Identified high-risk customers before potential revenue loss
</li>


<li>
Enabled personalized customer marketing strategies
</li>


<li>
Converted customer reviews into measurable insights
</li>


<li>
Improved understanding of customer lifetime behavior
</li>


<li>
Supported data-driven retention and growth strategies
</li>


</ul>



<hr>


<h2>Technology Stack</h2>


<ul>

<li>Python</li>

<li>Pandas & NumPy</li>

<li>SQL / SQLite</li>

<li>Scikit-learn</li>

<li>XGBoost</li>

<li>TensorFlow / Keras</li>

<li>Hugging Face Transformers</li>

<li>SHAP</li>

<li>Plotly</li>

</ul>



<hr>


<h2>Future Improvements</h2>


<ul>

<li>Real-time churn scoring API</li>

<li>Customer recommendation system</li>

<li>Automated model retraining pipeline</li>

<li>AI Platform</li>

<li>Marketing experiment evaluation</li>

</ul>
