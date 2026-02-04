# 🏛️ GovAssist AI — Right Scheme, Right Person, Right Documents  

**An AI-powered, voice-first assistant for inclusive access to government welfare schemes in India.**  

> Built for the **AWS AI for Bharat Hackathon** by **CYBERNETICS CREW BIT**

---

## 🌍 Problem Statement  

Millions of Indian citizens—especially in rural areas—fail to access welfare schemes due to:  

- Low digital literacy  
- Complex eligibility rules  
- Unclear document requirements  
- Language barriers  
- Dependence on middlemen  
- High application rejection rates  

As a result, deserving beneficiaries are excluded from critical social benefits.

---

## 💡 Our Solution — GovAssist AI  

**GovAssist AI** is an end-to-end intelligent assistant that helps citizens:

- Discover **eligible government schemes**
- Understand **why they qualify**
- Get a **document checklist**
- Fill forms **using voice**
- Reduce errors via **AI reconfirmation**
- Navigate directly to official portals  
- Receive simple, regional-language guidance  

### Motto  
> **“Right Scheme. Right Person. Right Documents.”**

---

## ✨ Key Features  

- 🎙️ **Voice-first access** using Bhashini APIs  
- 🧠 **Rule-based + AI eligibility engine**  
- 🔍 **Explainable AI (“Why Eligible?”)**  
- 📄 **Automatic document checklist generation**  
- 📝 **Voice-based form filling**  
- ✅ **Error prevention via reconfirmation loop**  
- 🔗 **Direct redirection to official portals**  
- ⚖️ **Constitution & rights-based knowledge layer**  
- 🔐 **Privacy-first design with minimal data collection**  

---

## 📊 Dataset Used  

We use the publicly available dataset:

🔗 **Indian Government Schemes Dataset (Kaggle)**  
https://www.kaggle.com/datasets/nitishabharathi/indian-government-schemes  

This dataset is processed and enriched with:

- Eligibility rules  
- Document mappings  
- Official form references  
- Portal links  

---

## ☁️ AWS Architecture  

GovAssist AI is built using a **scalable, serverless-first AWS stack**:

| Layer | AWS Service |
|------|-------------|
| Voice & Language | **Bhashini APIs** |
| AI Reasoning | **AWS Bedrock (LLM)** |
| OCR & Document Validation | **AWS Textract** |
| Backend APIs | **FastAPI on AWS Lambda / ECS** |
| Database | **PostgreSQL / DynamoDB** |
| File Storage | **AWS S3** |
| Monitoring | **AWS CloudWatch** |

---

## 🏗️ System Workflow  

1. User speaks in local language  
2. Bhashini converts speech to text  
3. AI extracts citizen profile  
4. Eligibility engine matches schemes  
5. Bedrock explains eligibility  
6. System returns document checklist  
7. User fills forms via voice  
8. AI reconfirms details  
9. Redirect to official portal  

---

## 🖥️ Tech Stack  

- **Frontend:** React / Gradio (MVP)  
- **Backend:** Python FastAPI  
- **AI:** AWS Bedrock  
- **OCR:** AWS Textract  
- **Storage:** AWS S3  
- **Database:** DynamoDB / PostgreSQL  
- **Speech:** Bhashini APIs  

---

## 🎯 Impact  

GovAssist AI aims to:

- Reduce application rejection rates  
- Minimize middlemen exploitation  
- Improve rural adoption of digital governance  
- Increase access to welfare schemes  
- Save citizens’ time and effort  

---

## 🧑‍🤝‍🧑 Team  

**Cybernetics Crew BIT**  
Birla Institute of Technology, Mesra (Jaipur Campus)

Team Lead: **Aryan Gaur**

---

## 🚀 Future Enhancements  

- Real-time grievance submission  
- Admin dashboard for NGOs/CSCs  
- Advanced recommendation engine  
- Aadhaar-based verification  
- Multi-language UI expansion  

---

## 📜 License  

MIT License — Free to use for educational and research purposes.

---

## 📞 Contact  

If you want to collaborate or learn more:

📧 Email: yashosw10@gmail.com  
🔗 GitHub: https://github.com/yashosw10  
🌐 LinkedIn: www.linkedin.com/in/yashowardhansw

📧 Email: aryangaur76731@gmail.com  
🔗 GitHub: https://github.com/Aryangaur-code  
🌐 LinkedIn: www.linkedin.com/in/aryan-gaur-bb8349293
