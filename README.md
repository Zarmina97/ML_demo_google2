<h1>Black Friday Dataset Analysis: <a href="eda.ipynb">EDA</a></h1>

<h2>Introduction</h2>
<p>Let's analyse just the <code>df_train</code> dataset for now. Here are some key observations:</p>

<h2>Observations</h2>
    <ul>
        <li><strong>User ID 1001680</strong> has the <strong>highest purchase count</strong> in the dataset, whereas <strong>User ID 1000708</strong> has the <strong>lowest</strong>.</li>
        <li><strong>Male customers</strong> have a higher purchase volume and also contribute to a greater financial expenditure overall.</li>
            <figure><img src="res/data exploration/gender_n_purchases.png" width=200, height=100></figure>
            <figure><img src="res/data exploration/gender_avg_purchases.png" width=200, height=100></figure>
        <li>The <strong>26-35 age bracket</strong> shows the highest quantity of items purchased, yet the expenditure is relatively uniform across all age groups.</li>
        <li>Individuals with <strong>occupation code 4</strong> stand out for purchasing significantly more items, though the spending is fairly consistent across different occupations.</li>
        <li><strong>City category B</strong> leads in the number of items purchased, while category C exhibits higher spending.</li>
        <li>Residents with a <strong>tenure of 1 year</strong> show the highest number of items purchased, but the spending is comparable up to a tenure of <strong>5+ years</strong>.</li>
        <li><strong>Single individuals</strong> make more purchases, but the expenditure is comparable to that of individuals who are married.</li>
    </ul>

<h2>Conclusion</h2>
<p>These insights provide a valuable understanding of the purchasing patterns within the <code>train</code> dataset, indicating specific trends in user behavior, demographic preferences, and financial expenditure.</p>
</body>
</html>
