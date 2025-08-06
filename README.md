#  IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies

This repository documents the **capstone project being developed** as part of the **IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies**. The internship is focused on helping students gain hands-on experience in emerging technologies, particularly in **Artificial Intelligence** and **IBM Cloud** services. 

The project involves building a **Network Intrusion Detection System (NIDS)** using machine learning techniques and deploying it through IBM Cloud. The objective is to identify and classify malicious network activity in real-time to enhance cybersecurity.

## 📝 Table of Contents

- [Intern Details](#intern-details)
- [About the Internship](#about-the-internship)
- [Project: Network Intrusion Detection System](#project-network-intrusion-detection-system)
  - [Problem Statement](#problem-statement)
  - [Solution Overview](#solution-overview)
- [Technology Stack](#technology-stack)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Repository Contents](#repository-contents)


## 👨‍💻 Intern Details

- **Name**: Saijal Tomar  
- **Institute**: Graphic Era Hill University 
- **Duration**: 4 Weeks (15th July 2025 – 7th August 2025)

## 📖 About the Internship

This 4-week program focused on providing practical experience in **Artificial Intelligence** and **Cloud Computing** using IBM Cloud tools. It included:

- **Week 1**: Internship Orientation, IBM Cloud Registration, Artificial Intelligence
- **Week 2**: Data Analytics concepts, Hands-On Labs, and Cloud EDA
- **Week 3 & 4**: Building a Chat Bot, AI/ML experiments on the cloud, and AutoAI usage on IBM Cloud

## 💡 Project: Network Intrusion Detection System
The  project under the IBM SkillsBuild Internship focuses on building a **Network Intrusion Detection System (NIDS)** using machine learning and IBM Cloud services. The aim is to develop an intelligent, cloud-deployed system that can detect and classify malicious network activities such as Denial of Service (DoS), Probe, Remote to Local (R2L), and User to Root (U2R) attacks.

# Problem Statement
Cyber-attacks such as DoS, R2L, U2R, and Probing are increasing in frequency and complexity. Traditional firewalls are often slow and ineffective in identifying new threats.
There is a need for an automated, intelligent system that can continuously monitor and classify network traffic — identifying anomalies and attacks as they happen.

# Solution Overview
This project proposes a machine learning-based Network Intrusion Detection System (NIDS) that uses the Kaggle intrusion detection dataset to classify network traffic as normal or malicious. After preprocessing the data, models such as Random Forest, SVM, and Snap Decision Tree  were trained and evaluated. The final, trained model was deployed as a real-time web service on the IBM Cloud platform using Watson Studio and Cloud Functions.

## ⚙️ Technology Stack
- **Cloud Platform**   : IBM Cloud
- **AI/ML Service**    : IBM watsonx.ai Studio                                  
- **Automated ML Tool** : IBM AutoAI (for training and model selection)
- **Storage Services**  : IBM Cloud Object Storage
- **Data Handling**     : Pandas
- **Langauage**         : Python
- **Libraries**         : Scikit-learn, XGBoost

## 🚀 Project Workflow
1. **Data Preprocessing**: Uploaded the labeled intrusion detection dataset (from kaggle) to IBM Cloud Object Storage, where AutoAI handled missing values, encoded categorical features, and scaled numerical data for training.

2. **Model Training**: Launched an AutoAI experiment in IBM watsonx.ai Studio, which automatically trained and optimized multiple ML models including Random Forest, SVM, and Snap Decision Tree.

3. **Model Evaluation**: AutoAI evaluated model pipelines using metrics like accuracy, precision, recall, and F1-score, selecting Snap Decision Tree as the best performer with ~94% accuracy.

4. **Model Deployment**: The best-performing model was deployed as a REST API using IBM Watson Studio, enabling real-time predictions through an endpoint hosted on IBM Cloud.

5. **Model Testing**: Used test network records to validate the deployed model's ability to correctly classify traffic as normal or malicious (DoS, Probe, R2L, U2R) in real time.

## 📊 Results

The Snap Decision Tree model, automatically selected and optimized by IBM AutoAI, achieved approximately 94% accuracy on the Kaggle intrusion detection dataset. It demonstrated strong performance across key evaluation metrics such as **precision**, **recall**, and **F1-score**. The model successfully classified various network intrusions — including DoS, Probe, R2L, and U2R — and was deployed as a real-time prediction service using IBM Watson Studio. Live testing confirmed its effectiveness in identifying both normal and malicious traffic accurately and consistently.
<img width="1440" height="900" alt="Screenshot 2025-08-02 at 8 45 24 PM" src="https://github.com/user-attachments/assets/0f4f1917-8d34-4185-a911-b4dfa44635df" /> 
<img width="1440" height="900" alt="Screenshot 2025-08-02 at 8 45 47 PM" src="https://github.com/user-attachments/assets/81ea511e-e33d-49bc-a2c4-a1218965ca52" /> 
<img width="1440" height="900" alt="Screenshot 2025-08-02 at 9 35 03 PM" src="https://github.com/user-attachments/assets/1038c152-909a-4195-a200-8e0bfe7af1f2" /> 

## 📁 Repository Contents
- `README.md` – Project documentation  
- `NIDS_Project.pptx` – Project presentation  

