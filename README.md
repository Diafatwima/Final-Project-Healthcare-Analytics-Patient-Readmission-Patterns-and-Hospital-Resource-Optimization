# Final-Project-Healthcare-Analytics-Patient-Readmission-Patterns-and-Hospital-Resource-Optimization
This project focuses on the exploratory data analysis of hospital patient records.The dataset contains key attributes such as 'Age,Gender,Department,Length of Stay Days,Total Cost USD,Comorbidities Count and Risk Level'.
Original Dataset from HCUP Nationwide Readmissions Database(NRD) Tools Used:Jupyter Notebook,python(Pandas,Matplotlib,seaborn,Plotly)
Obejectives of the project: *To analyze patient distribution across age,gender and departments.
*To study the relationship between Length of Stay Days and Total Treatment Cost.
*To identify cost-driving departments and resource-intensive patient groups.
*To v isualize significant patterns,correlation and anomalies in the data.
*To provide data-driven recommendations for gospital resource optimization.

METHODOLOGY
1.Data Loading&Cleaning-Checked fo null values,duplicates.Handled missing values.Readmitted 30 Days column had 100% null values and was dropped.
2.Data Transformation-Created new column Age_group using pd.cut() to group patients into<30,30-45,45-60,60-75,75+ categories.
3.Exploratory Data Analysis(EDA)-Used value counts(),groupby(),mean()and corr().
4.Data Visualization-Created 10 visualizations using Matplotlib,seaborn,plotly.
<img width="991" height="469" alt="image" src="https://github.com/user-attachments/assets/b99c91fb-adcc-4927-8391-169708361937" />
<img width="915" height="458" alt="image" src="https://github.com/user-attachments/assets/f1fd70db-81bc-4e8d-b409-43c2f297c9de" />
<img width="919" height="501" alt="image" src="https://github.com/user-attachments/assets/9c8f2eb1-ba5d-4afd-b7d7-e69a7ef02cde" />
<img width="817" height="444" alt="image" src="https://github.com/user-attachments/assets/2b5c9d99-331d-43a0-ab38-d2bb72f68f6a" />
<img width="925" height="499" alt="image" src="https://github.com/user-attachments/assets/d5cb27b7-43ee-43be-a05e-46a100b27539" />
<img width="1057" height="489" alt="image" src="https://github.com/user-attachments/assets/e59736d7-251f-4afc-a895-7a7bf5416f6a" />
<img width="594" height="493" alt="image" src="https://github.com/user-attachments/assets/11a9cd30-8cdb-4036-9f1d-3fec6d987935" />
<img width="808" height="409" alt="image" src="https://github.com/user-attachments/assets/def84b60-145b-4105-856a-3bb1b0c239d5" />
<img width="1018" height="182" alt="image" src="https://github.com/user-attachments/assets/edde61ae-51a4-4225-9f84-7c96a9c32328" />
