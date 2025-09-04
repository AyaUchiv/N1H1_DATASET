<h1>Vaccine Adoption Prediction<h1/>
  
<h2>Objectives And Methods</h2>
<p><b>Objectives: </b>Understand the key factors influencing vaccine uptake.</p>
<p><b>Methodology: </b>
Logistic regression model to predict vaccine uptake based on demographic and behavioral features.</p>

<h2>Exploration of Data</h2>
<h3>Training Data</h3>
<h4>Set Features</h4>
<p>35,000 attributes and 26,707 instances</p>
<h4>Labels</h4>
<p>2 attributes (decision attributes) and 26,707 instances</p>

<h3>Test Data</h3>
<h4>Set Features</h4>
<p>35,000 attributes and 26,707 instances</p>
<h4>Labels</h4>
<p>2 Unknown</p>

<h2>Data Analysis Workflow</h2>
<ol><li>Data PreProcessing</li>
<li>Training and Validating Model</li>
<li>Testing model</li></ol>

<h3>Data Preprocessing</h3>
<b>Handled missing values</b>
<p>Clear all NA in the dataset: 22,976 instances (a difference of 3,731)</p>
<b>Dropped Irrelevant Columns</b>
<ol>
  <li>Health_insurance</li>
  <li>Hhs_goe_region</li>
  <li>Employment_industry</li>
  <li>Employment_occupation</li>
</ol>

<h3>Extra</h3>
<ul>
  <li>Merged features and lables</li>
  <li>Converted decision attributes from binary to boolean ('yes', 'no')</li>
</ul>

<h2>Visualization and Interpretation of Results</h2>
<img width="1287" height="795" alt="image" src="https://github.com/user-attachments/assets/b9220697-d008-439d-aac9-804f7a39fc7e" />
