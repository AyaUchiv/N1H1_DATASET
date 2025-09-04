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

<h3>Feature Importance for H1N1 vaccine (using Coefficient Barchart)</h3>
<img width="1287" height="795" alt="image" src="https://github.com/user-attachments/assets/b9220697-d008-439d-aac9-804f7a39fc7e" />

<h3>Feature Importance for Seasonal vaccine (using Coefficient Barchart)</h3>
<img width="1405" height="791" alt="image" src="https://github.com/user-attachments/assets/e6be1e85-8ee6-4dac-8067-fa9bf8ed76a8" />

<h3>Interpretation</h3>
<p>Highlights the features which are important to whether a person will take the vaccine or not</p>
<b>Significant</b>
<ul>
  <li>Doctor’s recommendation, health worker status and vaccine opinions are highly predictive</li>
  <li>Age group (younger people) are less likely to take the vaccine</li>
  <li>Lower education and lower income are negatively correlated with vaccine uptake</li>
</ul>
<b>Non-Significant</b>
<ul>
  <li>Marital status had no bearing on decision to receive vaaccine or not</li>
  <li>Sexual  Orientation does not influence vaccine uptake</li>
  <li>H1N1 concern, behavioral factors (e.g., mask-wearing, avoidance), and handwashing are NOT significant.</li>
</ul>

<h3>Data Exploration</h3>
<b>Distribution of Predicted Probabilites for H1N1 Vaccine</b>

<img width="1358" height="746" alt="image" src="https://github.com/user-attachments/assets/f727186a-55ce-4883-83d5-144ac85eed6c" />

<b>Distribution of Predicted Probabilites for Seasonal Vaccine</b>

<img width="1295" height="728" alt="image" src="https://github.com/user-attachments/assets/115146f4-ba4d-4298-8c4a-a3d962c4ba44" />


<h2>Recommendation</h2>
<ol>
  <li>Doctors should actively recommend vaccines during patient visitations</li>
  <li>Innovative campaigns and outreaches to  encourage young adults to patronize the vaccines</li>
  <li>Social media campaign to calm fears of receiving the vaccine</li>
  <li>Vaccines should be more accessible to lower-income and minority groups</li>
  <li>Expand outreach on vaccine awareness to rural & remote areas with mobile clinics</li>
</ol>
