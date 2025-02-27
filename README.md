# 🌍 AI Travel Agent - Fully Automated Travel Planning 🚀

## ✈️ Overview

This AI-powered travel agent automates the entire trip-planning experience! Leveraging **Agentic AI**, it emulates a human travel agent by offering personalized travel recommendations, real-time bookings, and seamless communication — all without human intervention. 🌟

## 🎥 Demo

https://github.com/user-attachments/assets/e9f2ba12-07c6-4690-bc71-bf46635403de



## 🛠️ Features

- **Natural voice conversations with users** 🗣️  
- **Real-time flight & hotel searches** ✈️🏨  
- **Personalized travel itineraries** 📅  
- **Automated email summaries** 📧  
- **Collaboration of multiple AI agents** 🤖🤝  

## 🏗️ Tech Stack

- **n8n** - Workflow Automation ⚡
- **Eleven Labs** - Triggered via POST request 🔊
- **Gemini** - AI Language Model 🧠
- **Serp API** - Real-time Search 🔎
- **Tavily API** - Travel Data 📊
- **Gmail Integration** - Email Automation ✉️

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/AI-Travel-Agent.git
cd AI-Travel-Agent
```

### 2️⃣ Import Workflow into n8n
1. Open your **n8n** instance.
2. Navigate to the **Workflows** section.
3. Click on **Import** and upload the `Travel_Agent.json` file.

### 3️⃣ Configure API Keys & Tokens 🔑
Set up the required API keys and tokens in **n8n's credentials manager**:
- **Gmail Integration** - Uses Gmail app token for email automation.
- **Eleven Labs** - Triggered via HTTP POST request.
- **Serp API & Tavily API** - Used for real-time travel searches and recommendations.

### 4️⃣ Execute the Workflow 🎯
1. Start your **n8n** instance.
2. Trigger the workflow using the designated webhook URL.
3. Experience a fully automated travel planning service in action!

## 💡 How It Works

1. **User Interaction** - Users provide trip details through a conversational interface.
2. **Data Processing** - AI agents validate and refine the input data.
3. **Search Operations** - Real-time flight and hotel options are retrieved.
4. **Itinerary Generation** - A personalized travel itinerary is created.
5. **Communication** - The finalized itinerary is emailed to the user.

