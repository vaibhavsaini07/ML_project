# NSAP Applicant Classification using IBM Watsonx.ai

## 📘 Overview
This project automates the classification of applicants under the **National Social Assistance Programme (NSAP)** using **machine learning models** built on **IBM Watsonx.ai**.  
NSAP is a flagship welfare program by the Government of India, targeting **elderly citizens, widows, and persons with disabilities** in **Below Poverty Line (BPL)** households.

The solution replaces manual eligibility verification with a **multi-class classification model** that predicts the appropriate NSAP sub-scheme for each applicant based on **socio-economic and demographic data**.

---

## 🔍 Problem Statement
Manual verification of applications is **error-prone and time-consuming**, leading to delays in benefit distribution.  
There is a need for an **intelligent, automated system** that can efficiently assign the correct scheme to each applicant.

**Objective:**  
Build a **reliable machine learning classifier** to predict eligibility for:
- 🧓 **IGNOAPS** – Old Age Pension
- 👩‍🦳 **IGNWPS** – Widow Pension
- ♿ **IGNDPS** – Disability Pension

---

## 🛠️ Technologies Used
- ☁️ **IBM Cloud Lite** – Watson Studio, Cloud Object Storage  
- 🤖 **IBM Watsonx.ai** – AutoAI for automated ML pipeline generation  
- 🐍 **Python** – Data formatting & preprocessing  
- 📊 **Dataset** – AI Kosh NSAP Dataset  

---

## 📊 Model Training Process
- AutoAI trained **9 ML pipelines** using the provided dataset  
- **Best Model:** Decision Tree Classifier  
- **Accuracy:** 98%  
- Automatic **feature engineering** & **hyperparameter optimization**  

---

## 💡 Prediction & Deployment
- **Input:** Table or JSON format  
- **Output:** Predicted scheme + Class probabilities  
- **Real-time predictions** via IBM Watsonx.ai UI  
- Export-ready results in **Table** or **JSON** format  

---

## 📸 Results
### 🔷 AutoAI Pipeline Leaderboard


### ✅ Best Model Output Example

---

## 🔭 Future Scope
- Add more NSAP schemes and eligibility rules  
- Hybrid **Rule-based + ML classification** system  
- Aadhaar-linked verification for improved targeting  
- REST API deployment for **scalable bulk processing**  

---

## 🙏 Acknowledgements
- 💻 **IBM Cloud Academic Initiative**  
- 🇮🇳 **AI Kosh Dataset by IndiaAI**  
- 📚 **Government of India – Ministry of Rural Development**  

---

## 📜 License
This project is open-sourced under the **MIT License**.
