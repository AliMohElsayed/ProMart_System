# 🛍️ ProMart: Intelligent E-Commerce Toolkit Powered by AI & Automation 🚀

## 📌 Project Overview

**ProMart** is a smart, modular ecosystem built to enhance existing e-commerce platforms — not replace them. Instead of launching another store, ProMart delivers advanced tools, AI plugins, and automation solutions that help online businesses scale, personalize user experience, and make data-driven decisions with ease.

Built with Odoo, integrated with machine learning, and powered by semantic search and recommendation engines, ProMart brings the next generation of e-commerce to life.**.

## 🚀 Key Features

✅ Smart Search Engine: Understands user intent using semantic search via MiniLM.

✅ Personalized Recommendations: Collaborative filtering with SVD (Surprise library).

✅ Sales Forecasting: Time-series predictions with Prophet to optimize inventory & planning.

✅ Sentiment Analysis: Understand customer reviews with Multilingual BERT.

✅ Conversational AI Chatbot: Built using Gemini Flash 1.5 + RAG for real-time support in Arabic & English.

✅ Odoo Integration: Seamless business logic and data operations for inventory, users, and orders.

✅ Scalable Architecture: Ready to grow with your data, traffic, and business needs.

✅ User-Friendly Admin Tools: Visual dashboards, data insights, and intuitive controls.

---

## 🏗 System Architecture

### **1️⃣ AI Modules**

📌 **Platform** -	Built with Prophet (Meta) to model trends, seasonality, and holidays. 

📌 **Recommendation** - 	SVD-based matrix factorization using the Surprise library.  

📌 **Sentiment Analysis** - Uses nlptown/bert-base-multilingual-uncased-sentiment (via HuggingFace).

📌 **Chatbot** - LLM-powered assistant with Gemini Flash 1.5, integrated via RAG.  

📌 **Semantic Search** - Embedding-based retrieval using all-MiniLM-L6-v2 and ChromaDB. 

### **2️⃣  ML & NLP Flow**

1️⃣ Data Sources
Historical sales, products, and user interaction data (from Odoo)

Customer reviews and queries

2️⃣ Training & Tuning
SVD tuned using RMSE

Prophet evaluated with MAE & MAPE

Sentiment model pre-trained, used with HuggingFace’s pipeline

3️⃣ Deployment & Feedback Loop
Real-time updates via Odoo triggers

Embeddings stored in ChromaDB for fast lookup

Continuous improvement via user interaction


---

## 👥 Contributors  

| Name                 | Role                                                       |
| -------------------- | ---------------------------------------------------------- |
| **Ali Mohamed**      | Data Scientist - Data Analysist                            |
| **Ahmed Tarfa**      | ML Engineer                                                |
| **Marwa Atya**       | Odoo Expert                                                |
| **Manar Mohamed**    | NLP Specialist                                             |
| **Menna Shweel**     | Leader - Odoo Expert                                       |
| **Doaa Khamis**      | Frontend & UX/UI Design                                    |
| **Aya Ahmed**        | ML Engineer  -  UX/UI Design                               |
| **Mayar Mohamed**    | Recommender Systems                                        |

---

## 📬 Contact

📩 Connect with **Ali Mohamed** on **[LinkedIn](https://www.linkedin.com/in/ali-moh-sayed/)**.  

🚀 ProMart isn't just a project — it's a plug-and-play AI upgrade for the future of online shopping. 🛒
