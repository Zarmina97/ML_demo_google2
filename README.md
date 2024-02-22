<div align="center">
  <h1>Black Friday: Purchase Prediction</h1>
  <p><strong>Predicting Purchase amount for Black Friday data.</strong></p>
  <p>Tools used: Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn</p>
</div>
  <h2>Sections:</h2>
  <ul>
    <li><a href=#intro>Introduction</a></li>
    <li>Preprocessing and Feature Selection</li>
    <li>Model Building and Evaluation</li>
    <li>Final Prediction</li>
  </ul>
<h1 class='intro'>Introduction</h1>
<p>The classic Black Friday dataset is commonly used for data science and machine learning analyses, especially in challenges and projects that aim to understand consumer purchasing behaviour.</p>
    <h2>Business Objectives</h2>
     <ul>
        <li><strong>Understanding Consumer Behaviour:</strong> Identifying which products are most popular among different age groups, genders, and other demographic segments.</li>
        <li><strong>Customer Segmentation:</strong> Classifying customers into groups based on purchasing behaviour and preferences to customise offers and improve marketing strategies.</li>
        <li><strong>Stock Optimisation:</strong> Forecast demand for different product categories to better manage inventory.</li>
        <li><strong>Increased Sales:</strong> Identify the factors that most influence purchasing decisions to develop targeted promotions and increase sales.</li>
        <li><strong>Trend Analysis:</strong> Understand buying trends over time during Black Friday to adapt sales and marketing strategies.</li>
    </ul>

<h1>Black Friday Dataset Analysis: <a href="eda.ipynb">EDA</a></h1>
<p>Let's analyse just the <code>train</code> dataset for now. Here are some key observations:</p>

<h2>Observations</h2>
    <ul>
        <li><strong>User ID 1001680</strong> has the <strong>highest purchase count</strong> in the dataset, whereas <strong>User ID 1000708</strong> has the <strong>lowest</strong>.</li>
        <li><strong>Male customers</strong> have a higher purchase volume and also contribute to a greater financial expenditure overall.</li>
            <figure><img src="res/data exploration/gender_n_purchases.png" width=400, height=250></figure>
            <figure><img src="res/data exploration/gender_avg_purchases.png" width=400, height=250></figure>
        <li>The <strong>26-35 age bracket</strong> shows the highest quantity of items purchased, yet the expenditure is relatively uniform across all age groups.</li>
            <figure><img src="res/data exploration/age_n_purchases.png" width=400, height=250></figure>
            <figure><img src="res/data exploration/age_avg_purchases.png" width=400, height=250></figure>
        <li>Individuals with <strong>occupation code 4</strong> stand out for purchasing significantly more items, though the spending is fairly consistent across different occupations.</li>
            <figure><img src="res/data exploration/occupation_n_purchases.png" width=400, height=250></figure>
            <figure><img src="res/data exploration/occupation_avg_purchases.png" width=400, height=250></figure>
        <li><strong>City category B</strong> leads in the number of items purchased, while category C exhibits higher spending.</li>
            <figure><img src="res/data exploration/city_n_purchases.png" width=400, height=250></figure>
            <figure><img src="res/data exploration/city_avg_purchases.png" width=400, height=250></figure>
        <li>Residents with a <strong>tenure of 1 year</strong> show the highest number of items purchased, but the spending is comparable up to a tenure of <strong>5+ years</strong>.</li>
            <figure><img src="res/data exploration/residence_n_purchases.png" width=400, height=250></figure>
            <figure><img src="res/data exploration/residence_avg_purchases.png" width=400, height=250></figure>
        <li><strong>Single individuals</strong> make more purchases, but the expenditure is comparable to that of individuals who are married.</li>
            <figure><img src="res/data exploration/mstatus_n_purchases.png" width=400, height=250></figure>
            <figure><img src="res/data exploration/mstatus_avg_purchases.png" width=400, height=250></figure>
    </ul>

<h2>EDA Conclusion</h2>
<p>These insights provide a valuable understanding of the purchasing patterns within the <code>train</code> dataset, indicating specific trends in user behavior, demographic preferences, and financial expenditure.</p>

<h1>Black Friday - Regression models: <a href="feature engineering & models.ipynb">Feature engineering & models</a></h1>
Problem: Predict purchase amount.
    <h2>Machine Learning Use Case</h2>
    <p>To address this challenge, we employ several machine learning techniques, including linear regression, Lasso, Ridge, decision trees, Random Forest, Gradient Boosting Machine (GBM), XGBoost, LightGBM, and CatBoost. These models are used to predict the amount of purchases based on variables such as customer demographics, product information, and previous purchasing trends. Using a wide range of models allows us to assess which method provides the most accurate predictions and to identify the most significant factors influencing purchasing decisions.</p>
    <h2>Addressing the Business Goal with Machine Learning</h2>
    <p>The machine learning solution is expected to address the business goal by providing accurate predictions on the amount of customer purchases during Black Friday. By analysing predictive results from different models (Linear, Lasso, Ridge, Tree, RF, GBM, XGB, LGB, CB) compared to the original test data, we can identify which demographic factors and product categories have the greatest influence on purchase decisions. This allows us to customise offers for different customer segments, optimise stock based on demand forecasts and develop targeted marketing strategies to increase sales. Furthermore, by understanding purchasing trends over time, we can adapt our strategies to anticipate customer needs in future Black Friday events.</p>
</body>
</html>
