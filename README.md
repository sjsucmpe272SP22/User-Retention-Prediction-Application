## User Retention Prediction for Application Developers

User Retention Prediction for Application Developers

* Problem Statement:

  * For any app company that continuously monetized their users from their app, a potential challenge for them would be the user retention problem. They need a reliable and reusable method to simulate the retention rates of their users so that they can figure out which group of users are likely to be retained/churned. In this way, they can keep different users interested in their product by performing corresponding retention tasks.

* Abstract:

  * Simulated as a data analysis team, we fetch batched raw log data of the app from the dev/ops team, create and deploy a reliable and high accuracy cloud-hosted BigQuery machine learning model, to determine the likelihood rates of users continue to use the app based on the user behavior logs and user demographic information, and generate an insightful data visualization report to the product manager.

* Approach:

  * Pre-process the training data using the user's demographic and behavioral logs.
  * Train and evaluate machine learning models using BigQuery ML in GCP.
  * Make predictions using the terminative ML model and analyze the prediction result.
  * Perform feature engineering to generate important features and add to the training data space, and remove non-useful features.
  * Retrain ML model using the optimized training data to boost model reliability and accuracy.
  * Deploy finalized ML model using AI platform in GCP for real-time(dynamic) predictions.
  * Create an application data dashboard that performs visualization of data insights and prediction results.

* Technology Stack:

  * Python, Bigquery(SQL), GCP

* Dataset:
  * In this application, we will be using a public dataset provided by GCP: an event-based dataset that is generated by a real-world gaming mobile app called 'Flood-it!' that contains 5700000 event log info from more than 15175 users.
  * Dataset format: Google Analytics 4 property data and the Google Analytics for Firebase data that is exported to BigQuery Export schema
  * Dataset URL: <https://developers.google.com/analytics/bigquery/app-gaming-demo-dataset>
  * Flood-it! App URL: <https://flood-it.app/>

* Persona:
  * The product manager from the mobile game company ('Flood It!' in this case) who needs to know the user retention rate and corresponding analytic data regarding their game application. Knowing all these perceptive data would be significantly useful for them to design and maintain better targeted and customized user retention tasks on users in different retention categories, and bring positive financial impact to the company in the long run as a result.

* Architecture:
  * [System Architecture Diagram](System_Architecture.png)

* Results:
  * https://datastudio.google.com/u/3/reporting/c38fc4ea-009f-4514-8602-010c4cc3fa98/page/Gg3
  
