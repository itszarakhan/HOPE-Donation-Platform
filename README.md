# 🌟 HOPE – Hands Offering Positive Encouragement

## 📌 Project Overview
HOPE is a web-based donation platform designed to bridge the gap between donors and NGOs by providing a centralized, transparent, and user-friendly system for both monetary and material contributions.

The platform enables NGOs to list their specific needs and allows donors to contribute based on category and location. It also includes an intelligent chatbot system to assist users in real time.

---

## 🎯 Objectives
- Connect individual donors with NGOs through a single platform  
- Reduce waste by promoting donation of usable items  
- Simplify and organize the donation process  
- Ensure transparency and trust in transactions  

---

## 💡 Problem Statement
Many usable resources are wasted while NGOs struggle with shortages of essential items. The lack of a centralized and structured platform makes it difficult for donors to identify genuine NGOs and contribute effectively.

HOPE addresses this issue by providing a **secure, organized, and transparent donation system**.

---

## 🚀 Key Features
- 👤 User Registration & Authentication (Donor & NGO)  
- 💰 Dual Donation System (Monetary + Material)  
- 📍 City-wise NGO filtering  
- 🏷️ Category-based donation selection (Education, Disaster Relief, etc.)  
- 📊 Donation tracking dashboard  
- 🤖 Chatbot support using Machine Learning  
- 🧩 Community forum for interaction  

---

## 🧠 Tech Stack

### 🔹 Frontend
- HTML  
- CSS  
- JavaScript  

### 🔹 Backend
- Python  
- Django Framework  

### 🔹 Database
- SQLite3  

### 🔹 Machine Learning
- TF-IDF Vectorizer  
- Naive Bayes Classifier (for chatbot)

---

## ⚙️ System Methodology

### 1. Data Processing & Backend Logic
- Django MVT architecture used for structured development  
- ORM used for database operations  
- Secure authentication system implemented  

---

### 2. Donation System
- Monetary donations via platform  
- Material donation with item details (quantity, condition, deadline)  
- NGO verification for trust and authenticity  

---

### 3. Chatbot Module
- Built using TF-IDF + Naive Bayes  
- Trained on intent-based dataset (`intents.json`)  
- Integrated with Django backend  
- Provides real-time responses to user queries  

---

### 4. User Interaction
- Donor Dashboard → browse NGOs, donate, track contributions  
- NGO Dashboard → create requests, manage needs  
- Community Forum → discussions and engagement  

---

## 📊 Key Functionalities
- Secure login and registration system  
- Category-based and location-based NGO filtering  
- Real-time chatbot assistance  
- Donation request management system  
- Forum for community interaction  

---

## 🖥️ How to Run the Project

### Step 1: Clone the repository
```bash
git clone https://github.com/your-username/hope-donation-platform.git
cd hope-donation-platform
```

### Step 2: Install dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Run the server
```bash
python manage.py runserver
```

### Step 4: Open in browser
```
http://127.0.0.1:8000/
```

---