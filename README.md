# Kharcha Guru 🇮🇳💰
### Your AI-Powered Financial Companion & Government Scheme Guide

<div align="center">
  <img width="934" height="551" alt="Kharcha Guru Dashboard" src="https://github.com/user-attachments/assets/a3822842-8baf-4a74-b279-5a6fffff89c6" />
</div>

<br>

**Kharcha Guru** is an intelligent Telegram bot powered by **n8n** and **Google Gemini AI**. It doesn't just track your expenses; it acts as a proactive financial coach that finds hidden savings, suggests coupons, and maps your profile to eligible Government Welfare Schemes.

> *"Stop guessing where your money went. Start telling it where to grow."*

---

## 🚀 The Problem
- **Manual Tracking is Boring:** People hate entering data into Excel or complex apps.
- **Hidden Savings Lost:** Users unknowingly overspend on delivery fees and surge pricing (Zomato/Uber).
- **Information Gap:** Millions of Indians miss out on government benefits (like PMAY, Ayushman Bharat) simply because they don't know the eligibility or deadlines.

## 💡 The Solution: Kharcha Guru
Kharcha Guru lives in your chat app (Telegram/WhatsApp) and uses Multimodal AI to automate your financial life.

### Key Features

#### 1. 📸 Snap & Track (Expense Logging)
- **OCR Technology:** Simply upload a photo of a receipt or invoice.
- **Auto-Extraction:** The AI extracts the `Date`, `Amount`, `Category`, and `Merchant` automatically.
- **Natural Language:** Type "Spent 200 on Chai and Samosa" and it logs it instantly.

#### 2. 🧠 Smart Spending Insights (Wallet Leaks)
- **Behavior Analysis:** Detects recurring spending patterns.
- **Actionable Advice:**
  - *Too much Zomato?* Suggests using code `ZOMATO50` or buying Gold Membership.
  - *High Uber bills?* Recommends `Uber One` subscription to save mathematically.

#### 3. 🏛️ Government Scheme Mapper
- **Profile Matching:** Matches user age, income, and status to government schemes.
- **Real-time Info:** Provides deadlines, document lists, and application links for schemes like:
  - **PMAY** (Housing for All).
  - **CIDCO** (Affordable Housing Lotteries).
  - **Ayushman Bharat** (Health Cover).

#### 4. 🛡️ Financial Safety Net
- **Gap Analysis:** Identifies risks (e.g., high medical pharmacy bills).
- **Recommendations:** Suggests wealth protection tools like **Tata AIA Insurance** to save tax and cover emergencies.

---

## 🛠️ Tech Stack

* **Orchestration:** [n8n](https://n8n.io/) (Workflow Automation)
* **Interface:** [Telegram Bot API](https://core.telegram.org/bots)
* **Intelligence:** [Google Gemini 1.5 Pro](https://deepmind.google/technologies/gemini/) (Multimodal AI)
* **Database:** Google Sheets / PostgreSQL
* **Search:** Google Custom Search API (For real-time scheme deadlines)

---

## 💰 Business Model

Kharcha Guru is designed with a sustainable dual-revenue stream:

1.  **Freemium Model:** Basic tracking is free. Advanced Reports & "Guru Coaching" are part of a Premium Subscription.
2.  **Affiliate Engine:**
    * **Insurance:** Partner links for Health/Life Insurance (e.g., Tata AIA).
    * **Credit Cards:** Recommendations based on spending habits.
    * **Subscriptions:** Affiliate revenue from platforms like Zomato/Uber.

---

## ⚙️ How It Works (The Workflow)

1.  **User Input:** User sends a text or image to the Telegram Bot.
2.  **n8n Webhook:** Receives the data.
3.  **AI Analysis:**
    * If **Image:** Gemini Vision extracts data.
    * If **Text:** Gemini NLP categorizes intent.
4.  **Database Action:** Data is cleaned and stored.
5.  **Coaching Layer:** The AI checks for "Wallet Leaks" or "Scheme Eligibility."
6.  **Response:** A formatted HTML message is sent back to the user with actionable advice.

---

## 🚀 Getting Started

To run this project locally:

1.  **Clone the Repo**
2.  **Import Workflow:** Import the `.json` file into your self-hosted n8n instance.
3.  **Credentials:**
    * Set up a Telegram Bot via `@BotFather` and get the API Token.
    * Get a Google Gemini API Key.
    * Connect your Google Sheets account.
4.  **Activate:** Turn on the workflow and start chatting with **Kharcha Guru**!

---
