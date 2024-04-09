# DiabTableauProj

Diabetes Dashboard 

This interactive Tableau dashboard provides an in-depth look at diabetes prevalence, demographics, and key health indicators. By visualizing data from a survey of over 100,000 individuals, the dashboard offers valuable insights for healthcare providers, researchers, and policymakers seeking to understand and address the diabetes epidemic.

The data was collected from Kaggle.com:  https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset

The data needed to be converted from ‘1’s and ‘0’s to strings in the ‘hypertension’, ‘heart_disease’, and ‘diabetes’ columns.  The manipulation and changing of the data were done with jupyter notebook:
- The ‘hypertension’ column was labeled as ‘0’ for ‘not hypertensive’ and ‘1’  for ‘hypertensive’
- The ‘heart_disease’ column was labeled as ‘0’ for ‘no heart disease’ and ‘1’  for ‘heart disease’
- The ‘diabetes’ column was labeled as ‘0’ for ‘not diabetic’ and ‘1’  for ‘diabetic’

After uploading the csv, I noticed the visualizations would be easier to work with and manipulate if I created reference ranges for the ‘bmi’, ‘HbA1c_level’, and ‘blood_glucose_level’.  The reference ranges that I used were referenced from the CDC, National Institutes of Health, and the World Health Organization.

The way I created the references in Tableau is by creating loops and ‘If’ statements:
- ‘bmi_ranges’ 
- ‘Glucose Ranges’ 
- ‘HbA1c Ranges’
 
After manipulation of the data I was able to create a dashboard with dropdowns of ‘Gender’, ‘BMI’, ‘Diabetes’, and ‘HbA1c Range’, and displaying 3 different visuals with ‘Glucose Ranges’, ‘Smoking History’, and ‘Heart Disease and No Heart Disease’. 

References:
https://www.who.int/data/gho/indicator-metadata-registry/imr-details/2380
https://www.cdc.gov/diabetes/managing/managing-blood-sugar/a1c.html
https://www.nhsinform.scot/healthy-living/food-and-nutrition/healthy-eating-and-weight-loss/body-mass-index-bmi/

Tableau:  https://public.tableau.com/views/DiabetesTableau_17120269730270/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link


