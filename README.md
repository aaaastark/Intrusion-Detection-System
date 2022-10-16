# Attack Detection, Parameter Optimization and Performance Analysis in Enterprise Networks (ML Networks) for Intrusion Detection System IDS.


#### Research Paper: Attack Detection in Enterprise Networks by Machine Learning Methods
- Website Link for Paper: [Attack Detection in Enterprise Networks by Machine Learning Methods](https://ieeexplore.ieee.org/document/8867696)

#### Research Paper: Parameter Optimization and Performance Analysis of State-of-the-Art Machine Learning Techniques for Intrusion Detection System (IDS)
- Website Link for Paper: [Parameter Optimization and Performance Analysis of State-of-the-Art Machine Learning Techniques for Intrusion Detection System (IDS)](https://ieeexplore.ieee.org/document/9392683)

#### Loading the dataset (Canadian Institute for Cybersecurity) Intrusion Detection Evaluation Dataset (CIC-IDS2017)
- Website Link for Dataset: [Intrusion Detection Evaluation Dataset (CIC-IDS2017)](https://www.unb.ca/cic/datasets/ids-2017.html)
##### CICIDS2017 dataset contains benign and the most up-to-date common attacks, which resembles the true real-world data (PCAPs). It also includes [the results of the network traffic analysis](https://github.com/ahlashkari/CICFlowMeter) using CICFlowMeter with labeled flows based on the time stamp, source, and destination IPs, source and destination ports, protocols and attack (CSV files).

#### Loading the dataset (Canadian Institute for Cybersecurity) Communications Security Establishment (CSE) & the Canadian Institute for Cybersecurity (CIC) *CSE-CIC-IDS2018 on AWS*
- Website Link for Dataset: [Communications Security Establishment (CSE) & the Canadian Institute for Cybersecurity (CIC) *CSE-CIC-IDS2018 on AWS*](https://www.unb.ca/cic/datasets/ids-2018.html)
##### In CSE-CIC-IDS2018 dataset, we use the notion of profiles to generate datasets in a systematic manner, which will contain detailed descriptions of intrusions and abstract distribution models for applications, protocols, or lower level network entities. 

<p align="center" width="100%">
    <img width="100%" hight="100%" src="https://user-images.githubusercontent.com/74346775/196039859-28c96e2b-e5a2-4208-9959-67894ad42abf.png"> 
</p>

#### Workflow that is used in this Project
- Data Processing (ETL, Wrangling)
- Data Normalization
- Binary Class Classification
- Multi Class Classification
- Feature Extraction (BC and MC)
- LightGBM and XGBoost (Gradient Boosting)
- Visualization (Classification Report and Ploat Confusion Matrix)
- Accuracy, Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, and R2 Score

#### APIs that are used in this Project
- tensorflow
- sklearn
- keras
- lightgbm
- catboost
- matplotlib
- numpy
- pandas

## Paper vs Proposed Results: *Attack Detection, Parameter Optimization and Performance Analysis in Enterprise Networks (ML Networks) for Intrusion Detection System IDS.*

#### Binary Class Classification (Proposed Results): LightGBM (Gradient Boosting)
<p align="center" width="100%">
    <img width="33%" src="https://user-images.githubusercontent.com/74346775/196040655-4750ed79-980a-44f1-9659-1880ccab31d9.png"> 
    <img width="33%" src="https://user-images.githubusercontent.com/74346775/196040699-5cd491ab-3f7d-42f9-bada-6b4cb00007ae.png"> 
    <img width="33%" src="https://user-images.githubusercontent.com/74346775/196040766-084efabc-db16-4780-a6c4-45f9b927885a.png"> 
</p>

#### Binary Class Classification (Proposed Results): XGBoost (Gradient Boosting)
<p align="center" width="100%">
    <img width="33%" src="https://user-images.githubusercontent.com/74346775/196040876-99a24d46-dc02-4eee-9c2e-3333902cdf49.png"> 
    <img width="33%" src="https://user-images.githubusercontent.com/74346775/196040893-5072cacb-70d6-474a-b962-daa509256112.png"> 
    <img width="33%" src="https://user-images.githubusercontent.com/74346775/196040905-cca94fbc-5a60-4db1-a5c0-fecbe895a20b.png"> 
</p>

