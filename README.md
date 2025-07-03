# 🛍️ ProMart – AI-Powered E-Commerce Platform Integrated with Odoo

## 📌 Project Overview

**ProMart** is our graduation project, is a smart, modular ecosystem built to enhance existing e-commerce platforms — not replace them. Instead of launching another store, ProMart delivers advanced tools, AI plugins, and automation solutions that help online businesses scale, personalize user experience, and make data-driven decisions with ease.

Built with Odoo, integrated with machine learning, and powered by semantic search and recommendation engines, ProMart brings the next generation of e-commerce to life.

---

## 🎥 Demo Video

<img src="https://s3.ezgif.com/tmp/ezgif-32d36a64134c20.gif" width="700"/>

👉 [Click here to Show our project](https://drive.google.com/file/d/1lp5cvyLxJRdhzXiU5pMvPevoypUYezS6/view?usp=sharing)

---

## 🚀 Key Features

### 🤖 1. Assel – AI Sales Chatbot
- Built with **Gemini Flash 1.5**
- Talks in **Arabic and English**
- Recommends products using **RAG (Retrieval-Augmented Generation)**
- Uses **ChromaDB** as a vector store for semantic search
- Pulls live inventory data from Odoo

### 💬 2. EchoSent – Sentiment Analysis
- Fine-tuned **Hugging Face LLM** to support Arabic reviews
- Predicts customer sentiment (rating from 1 to 5)
- Can be integrated with future social media monitoring tools

### 🔍 3. SeekSense – Vector-Based Product Search
- Replaces traditional keyword search
- Handles **spelling mistakes and vague queries**
- Uses **cosine similarity** with vector embeddings

### 📈 4. Seerly – Sales Forecasting
- Uses **Facebook Prophet** with **grid search optimization**
- Predicts daily sales based on admin parameters
- Helps admins make data-driven decisions

### 🎯 5. Aletheia Recommendation Engine
- Personalized product recommendations using **SVD (Singular Value Decomposition)**
- Learns from each customer’s purchase history and ratings

### 🎯 6. Odoo
We integrated ProMart with **Odoo ERP** to take advantage of its robust features:
- Admin can manage inventory, customers, and products
- Real-time sales dashboards
- Seamless integration with our ML models
- Handles automated emails for sign-up, purchase, and password reset

---

## 👤 Roles

### 👨‍💼 Admin:
- Full control over inventory, product catalog, and customer data
- View real-time dashboards and forecasts with **Seerly**
- Analyze customer feedback using **EchoSent**

### 🛍️ Customer:
- Smart search via **SeekSense**
- Personalized recommendations via **Aletheia**
- Real-time AI assistance through **Assel chatbot**
- Auto email notifications on key actions

---

## 🏗 System Architecture

### **1️⃣  ML & NLP Flow**

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

| **Ali Mohamed**     | **Ahmed Tarfa**   |
| **Marwa Atya**      | **Manar Mohamed** |
| **Menna Shweel**    | **Doaa Khamis**   |
| **Aya Ahmed**       | **Mayar Mohamed** |

---

## 📬 Contact

📩 Connect with **Ali Mohamed** on **[LinkedIn](https://www.linkedin.com/in/ali-moh-sayed/)**.  

🚀 ProMart isn't just a project — it's a plug-and-play AI upgrade for the future of online shopping. 🛒
