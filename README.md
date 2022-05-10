## User Retention Prediction for Application Developers

User Retention Prediction for Application Developers

* Problem Statement:

  * For any app company that continuously monetized their users from their app, a potential challenge for them would be the user retention problem. They need a realiable and reuseable method to simluate the retention rates of their users so that they can figure out which group of users are likely to be retained/churned. In this way, they can later on keep different users interested in their product by performing corresponidng retention task.

* Abstract:

  * Simulated as a data analisis team, we fetch batched raw log data of the app from the dev/ops team, create and maintain a reliable and high accuracy cloud hosted BigQuery machine learning model, to determine the likelihood rates of users continue to use the app based on the user behaverior logs and user demographic information, 

* Approach:

  * Pre-process the training data using user's demographic and behavioural logs. 
  * Train and evaluate machine learing models using BigQuery ML in GCP.
  * Make predictions using the terminative ML model and analyze the prediction result.
  * Perform feature engineering to generate improtant features and add intoto the trainning data space, and remove non-useful features.
  * Retrain ML model using the optmized trainning data to boost model relibility and accuracy. 
  * Deploy finalized ML model using AI platform in GCP for real-time(dynamic) predictions.
  * Create an application data dashboard which perform visualization of data insights and prediction results.

* Technology Stack:

  * Python, Bigquery(SQL), GCP

* Dataset:
  * In this application, we will be using a public dataset provided by GCP: an event based dataset which is generated by a real-world gaming mobile app called 'Flood-it!' that contains 5700000 event log infos from more than 15175 users.
  * Dataset format: Google Analytics 4 property data and the Google Analytics for Firebase data that is exported to BigQuery Export schema
  * Dataset URL: https://developers.google.com/analytics/bigquery/app-gaming-demo-dataset
  * Flood-it! App URL: https://flood-it.app/ 

* Persona:
  * The product manager from the mobil game company ('Flood It!' in this case) who need to know the user retention rate and coresspoinding analytic data regarding their game aplication. Knowing all these perceptive data would be significantly useful for them to design and maintain better targetd and customized user retention task on user in different retention categories, and bring postive financial impact to the company at the long run as an result.

