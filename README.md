# credit-card-approval-repo
## Predicting the result of Credit card applications using Logistic Regression

<p>Commercial banks receive <em>a lot</em> of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this notebook, I've built an automatic credit card approval predictor using machine learning techniques, just like the real banks do.</p>

<p>I've used the <a href="http://archive.ics.uci.edu/ml/datasets/credit+approval">Credit Card Approval dataset</a> from the UCI Machine Learning Repository.<br>The structure of this notebook is as follows:</p>
<ul>
<li>First, I started off by loading and viewing the dataset.</li>
<li>The dataset has a mixture of both numerical and non-numerical features, that it contains values from different ranges, plus that it contains a number of missing entries.</li>
<li>Then, I preprocessed the dataset to ensure the machine learning model we choose can make good predictions.</li>
<li>After the data gets into good shape, I did some exploratory data analysis to build intuitions.</li>
<li>Finally, I built a machine learning model that can predict if an individual's application for a credit card will be accepted.</li>
</ul>
