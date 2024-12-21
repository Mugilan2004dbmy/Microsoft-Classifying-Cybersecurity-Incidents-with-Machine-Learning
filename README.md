# **🔐 Microsoft-Classifying-Cybersecurity-Incidents-with-Machine-Learning**  

## **🌐 Introduction:**  
**Classifying Cybersecurity Incidents with Machine Learning** utilizes advanced algorithms to automatically detect and categorize cybersecurity threats. By analyzing vast amounts of security data for patterns and anomalies, machine learning boosts the speed, precision, and efficiency of incident classification. This method enables organizations to respond proactively to emerging threats, decrease manual intervention, and reinforce their security defenses in an ever-changing digital environment.  

## **🎯 Objective:**  
The goal of **Classifying Cybersecurity Incidents with Machine Learning** is to create an automated system that can:  
1. **🔍 Identify and categorize** cybersecurity incidents based on their type and severity.  
2. **⏱️ Speed up response times** by quickly detecting patterns and anomalies in security data.  
3. **🤖 Reduce manual effort** in incident analysis through intelligent automation.  
4. **🎯 Enhance accuracy** in threat detection and classification.  
5. **🛡️ Strengthen security measures** by enabling proactive threat management.  

This approach aims to make cybersecurity systems more efficient, scalable, and resilient against evolving cyber threats.  

## **📊 Dataset Overview:**  
The dataset consists of labeled cybersecurity incident records with key attributes:  

- **🛑 Incident Type**: Malware, phishing, DDoS, etc.  
- **📅 Timestamp**: Date and time of incidents.  
- **🌐 Source/Target IP**: Attack origin and target.  
- **🛠️ Attack Vector**: Methods used for attacks.  
- **⚠️ Severity Level**: Low, Medium, High.  
- **📜 Log Details**: System logs and alerts.  

**Sources** include network logs, IDS reports, and public datasets like **CICIDS2017** or **NSL-KDD**. The target variable represents the type of cybersecurity incident.  

## **💼 Business Use Cases:**  
1. **🚨 Incident Detection & Classification**: Automate identification of cyber threats like malware, phishing, or DDoS attacks.  
2. **⚡ Threat Prioritization**: Classify incidents by severity (Low, Medium, High) for faster response.  
3. **🔍 Anomaly Detection**: Detect unusual patterns in network traffic or user behavior.  
4. **🤖 Automated Response Systems**: Trigger real-time alerts or actions for critical threats.  
5. **💡 Resource Optimization**: Minimize manual analysis and boost security team efficiency.  
6. **📑 Compliance & Reporting**: Ensure regulatory compliance by accurately logging and categorizing incidents.  

## **📊 Model Comparison with Accuracy Score:**  
The table below presents an overview of the performance of various models, summarized by their accuracy scores. This comparison highlights the effectiveness of each model in predicting cybersecurity incidents.

| **Model**               | **Accuracy** |
|-------------------------|-------------:|
| Logistic Regression     | 0.6509       |
| Decision Tree           | 0.6743       |
| Random Forest           | 0.6756       |
| Gradient Boosting       | 0.6712       |
| SVM                     | **0.6952**   |
| KNN                     | 0.6694       |

**🏆 Best Model**: **SVM** with Accuracy **0.6952**.  

## **🏁 Result:**  
This project demonstrated the successful use of machine learning to classify cybersecurity incidents using historical data. The **SVM** (Support Vector Machine) model emerged as the top performer, offering a strong balance of accuracy, precision, and recall across all incident categories. By employing techniques such as hyperparameter tuning (via RandomizedSearchCV) and exploring feature engineering, the model achieved an enhanced Macro-F1 score, making it highly effective for complex cybersecurity data. Further optimizations, including additional hyperparameter adjustments and feature engineering, could further elevate the model's performance. This approach provides a valuable tool for Security Operations Centers (SOCs) to prioritize and tackle cybersecurity threats more efficiently, ultimately improving response times and threat mitigation.
