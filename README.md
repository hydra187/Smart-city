# 🏙️ Smart City Command Center

A real-time smart city dashboard that aggregates multiple live data sources and integrates an AI assistant to provide contextual insights.

## 🚀 Problem Statement

Modern cities generate massive amounts of data (weather, economy, citizens, etc.), but it's scattered across platforms.

This project solves that by:
- Centralizing city data into one dashboard
- Making it interactive and user-friendly
- Adding an AI layer to interpret the data

## ✨ Key Features

- 🌦️ Live Weather Data (API integration)
- 💱 Real-time Currency Exchange Rates
- 👤 Dynamic Citizen Profile Display
- 💡 Random City Insights
- 🤖 AI Assistant (via OpenRouter API)
- 🎨 Modern UI (Glassmorphism + responsive design)

## 🧠 Technical Highlights

- Integrated **multiple APIs simultaneously**
- Built **AI-powered assistant** using OpenRouter
- Handled **async data fetching + error states**
- Used **environment variables for secure API handling**
- Designed a **modular and scalable frontend structure**

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Build Tool:** Vite
- **APIs:** OpenRouter, Open-Meteo, ExchangeRate, Reqres
- **Concepts:** API Integration, Async JS, State Handling

## ⚙️ Setup & Installation

```bash
git clone https://github.com/hydra187/Smart-city.git
cd Smart-city
npm install
npm run dev
