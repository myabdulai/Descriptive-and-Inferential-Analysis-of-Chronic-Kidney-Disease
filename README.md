<h1>Descriptive and Inferential Analysis of Chronic Kidney Disease</h1>

<p>
This project combines <strong>interactive data visualization</strong> and 
<strong>statistical modeling</strong> to analyze risk factors associated with 
<strong>Chronic Kidney Disease (CKD)</strong> using a synthetic clinical dataset.
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
The project was completed in two main parts:
</p>

<ul>
    <li>
        <strong>Part 1:</strong> Development of an interactive <strong>Power BI dashboard</strong> 
        for descriptive analysis of CKD risk factors.
    </li>
    <li>
        <strong>Part 2:</strong> Application of <strong>logistic regression</strong> using Python 
        to identify variables significantly associated with CKD.
    </li>
</ul>

<p>
A synthetic medical dataset sourced from Kaggle was used for analysis.
</p>

<hr>

<h2>📊 Part One: Power BI Dashboard</h2>

<p>
An interactive Power BI dashboard was built to explore and compare patients with 
<strong>CKD</strong> and <strong>No CKD</strong>. The dashboard allows users to filter 
between groups using a button-based slicer, with all visuals updating in real time.
</p>

<h3>Key Dashboard Metrics</h3>

<ul>
    <li>Total of patients</li>
    <li>Average age</li>
    <li>Average glomerular filtration rate (GFR)</li>
    <li>Average serum creatinine</li>
    <li>Average blood urea nitrogen (BUN)</li>
    <li>Average urinary output</li>
    <li>7Total patients by diabetes status</li>
    <li>Total patients by hypertension status</li>
</ul>

<p>
Bar charts highlight the distribution of <strong>diabetes</strong> and 
<strong>hypertension</strong>, two major CKD risk factors. Consistent color semantics 
are applied across visuals to improve interpretability and reduce cognitive load.
</p>

<hr>

<h2>📈 Part Two: Inferential Analysis (Logistic Regression)</h2>

<h3>Methodology</h3>

<ul>
    <li>Binary logistic regression model</li>
    <li>80/20 stratified train-test split</li>
    <li>5-fold cross-validation on training data</li>
    <li>Performance evaluation using AUC and accuracy</li>
    <li>Calibration assessment using reliability curve and Brier score</li>
</ul>

<h3>Key Findings</h3>

<ul>
    <li>
        <strong>Creatinine</strong> and <strong>BUN</strong> showed strong positive 
        associations with CKD.
    </li>
    <li>
        <strong>GFR</strong> demonstrated a strong protective effect, with higher values 
        associated with lower CKD odds.
    </li>
    <li>
        <strong>Urine output</strong> showed a modest protective association.
    </li>
    <li>
        Age, diabetes, and hypertension were not statistically significant after adjusting 
        for kidney function variables.
    </li>
</ul>

<p>
The final model achieved good discrimination and calibration, with a 
<strong>Brier score of 0.1204</strong>, indicating reliable probability estimates.
</p>

<hr>

<h2>🧠 Key Skills Demonstrated</h2>

<ul>
    <li>Power BI dashboard design and data modeling</li>
    <li>DAX measures and interactive slicers</li>
    <li>Clinical data visualization</li>
    <li>Logistic regression modeling in Python</li>
    <li>Model evaluation, calibration, and interpretation</li>
    <li>Applied health informatics analytics</li>
</ul>

<hr>

<h2>📁 Tools & Technologies</h2>

<ul>
    <li>Power BI</li>
    <li>Python (pandas, statsmodels / scikit-learn, matplotlib)</li>
    <li>Logistic Regression</li>
    <li>Healthcare & Clinical Analytics</li>
</ul>

<hr>

<h2>📌 Notes</h2>

<p>
This project uses a synthetic clinical dataset to demonstrate applied healthcare analytics,
combining interactive dashboards with statistical modeling to generate interpretable insights relevant to population health and clinical decision support.
</p>

</body>
</html>

<h2>📂 Data Source</h2>

<p>
The dataset used in this project is a synthetic clinical dataset obtained from Kaggle:
</p>

<p>
<a href="https://www.kaggle.com/datasets/mansoordaku/ckdisease" target="_blank">
https://www.kaggle.com/datasets/miadul/kidney-disease-risk-dataset
</a>
</p>

<p>
The dataset was used strictly for academic and portfolio purposes.
</p>
