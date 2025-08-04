# Predicting-Container-Availability-Matson-s-China-Service-ASU
Overview
Developed an end-to-end predictive machine learning pipeline in collaboration with Matson, Inc. and Arizona State University to forecast which cargo containers would be picked up within 24 hours of vessel arrival. The solution enabled better stowage planning and reduced yard congestion, driving significant operational efficiencies at port terminals.

Problem Statement
Matson sought to improve container yard operations by accurately forecasting which containers would be collected within 24 hours after vessel arrival. Accurate predictions were expected to reduce rehandling costs, optimize yard space, and enhance overall customer satisfaction.

Data & Features
Data Sources: Internal Matson shipment and port operations data

Raw Attributes: 90+ features including consignee behavior, vessel schedules, pickup history, container characteristics, and yard logistics

Engineered Features: 29+ new features created to improve model signal and performance

Methodology & Tools
Feature Engineering: Data preprocessing, aggregation, transformation, and creation of predictive variables

Modeling: LightGBM classifier; hyperparameter tuning for optimal recall and AUC

Deployment: AWS Lambda, S3, SageMaker, and API Gateway for a fully serverless, scalable inference pipeline

Visualization: Delivered actionable dashboards for planners

Solution & Implementation
Engineered and selected the most predictive features from a wide pool of raw operational data

Trained and evaluated multiple models, ultimately deploying LightGBM (95% recall, 0.89 AUC)

Designed a serverless real-time and batch inference pipeline on AWS (Lambda, S3, SageMaker, API Gateway)

Built dashboards and delivered insights to Matson planners, empowering more informed decisions

Results & Impact
Reduced rehandling costs and port yard congestion

Improved terminal efficiency through data-driven stowage planning

Boosted customer satisfaction by decreasing wait times and streamlining pickup

Actionable dashboards enabled data-driven decision-making for Matson’s operations teams

Key Takeaways
Delivered measurable operational and financial impact to a Fortune 500 logistics company

Gained hands-on experience deploying ML pipelines using AWS serverless technologies

Demonstrated the value of combining advanced analytics with business process optimization

Future Work / Improvements
Integrate live vessel tracking and weather data for even more robust predictions

Deploy automated notifications to stakeholders based on prediction outcomes

Tech Stack
Python, Pandas, NumPy

AWS Lambda, SageMaker, S3, API Gateway

LightGBM

Tableau (or another BI tool for dashboards)

How to Run / Use
This project used confidential Matson data and proprietary AWS infrastructure. A sanitized notebook or sample code demonstrating the pipeline and ML workflow can be provided on request.

