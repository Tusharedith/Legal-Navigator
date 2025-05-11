# 🧭 Legal Navigator

**Legal Navigator** is an AI-powered legal assistance platform that simplifies legal information for everyone — from students and professionals to individuals dealing with legal issues. It uses the power of natural language processing and intelligent APIs to provide instant, personalized, and reliable legal support.

---

## 🌐 Live Demo

> *Coming soon or deploy via your preferred platform (Render, Heroku, or Streamlit sharing)*

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Architecture & APIs](#architecture--apis)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## 📖 Project Overview

Legal Navigator is designed to demystify legal jargon, deliver up-to-date legal news, and guide users through their legal queries via a conversational chatbot. It uses **ChatGPT API** for natural conversation and **Google APIs** (e.g., News API, Search API) to fetch and filter relevant legal news content.

The goal is to create a legal co-pilot that empowers users to become informed and take the right legal steps with confidence.

---

## 🧠 Key Features

### 💬 AI-Powered Chatbot (ChatGPT API)
- Offers instant legal advice and explanations.
- Handles diverse legal topics such as labor laws, civil rights, contracts, and more.
- Powered by OpenAI’s GPT-4 API for accurate and conversational responses.

### 📰 Legal News Headlines (Google News API)
- Aggregates and filters legal news from verified sources.
- Keeps users informed of recent court rulings, amendments, and policy changes.

### 🎯 Personalized News Suggestions
- Uses user preferences and history to provide curated legal news.
- Offers keyword-based search and filtered content through Google APIs.

### 📚 Legal Knowledge Base
- A built-in FAQ and glossary to break down complex legal concepts.
- Helps users understand their rights and processes in simpler terms.

### ⚙️ Admin-Friendly Backend
- Flask-based server that manages API calls and renders frontend content.
- Modular design for easy integration of additional APIs and services.

---

## 🛠️ Tech Stack

| Layer        | Technology / Tool                       |
|--------------|------------------------------------------|
| Frontend     | HTML5, CSS3, JavaScript, Bootstrap       |
| Backend      | Python, Flask                            |
| AI Engine    | OpenAI ChatGPT API (GPT-4)               |
| News Feed    | Google News API / Google Custom Search   |
| Database     | SQLite (or any other optional DBMS)      |

---

## 🔌 Architecture & APIs

### ChatGPT API (OpenAI)
- Endpoint: `https://api.openai.com/v1/chat/completions`
- Model: `gpt-4`
- Purpose: Understand user queries and provide contextual legal assistance.

### Google News/Search API
- Endpoint: `https://www.googleapis.com/customsearch/v1`
- Filters legal news articles using legal-related queries.
- Displays headlines and snippets in the news section.

> Note: You will need API keys for both Google and OpenAI. These keys should be stored securely (e.g., in environment variables or a `.env` file).

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Tusharedith/Legal-Navigator.git
cd Legal-Navigator
```

2. Install Required Packages
Make sure you have Python 3.x installed.

```bash
pip install -r requirements.txt
```
3. Set Environment Variables
Create a .env file in the root directory and add your API keys:
```bash
OPENAI_API_KEY=your_openai_key_here
GOOGLE_API_KEY=your_google_api_key_here
CUSTOM_SEARCH_ENGINE_ID=your_cse_id_here
```
5. Run the Application
```bash
python app.py
```
7. Access the Web App
Open your browser and go to:
http://localhost:5000

🖼️ Screenshots
<p align="center"><img src="https://github.com/Tusharedith/Legal-Navigator/blob/main/ScreenShots/Screenshot%202024-03-20%20201555.png? raw=true" height="40%" width="33%" alt="Login">
<img src="https://github.com/Tusharedith/Legal-Navigator/blob/main/ScreenShots/01.png?raw=true" width="33%" alt="Home Page">
<img src="https://github.com/Tusharedith/Legal-Navigator/blob/main/ScreenShots/05.png?raw=true" width="33%" alt="Chatbot Interaction"> </p>
🧪 Usage

<br>
⭐ Start the server.<br>
⭐ Navigate to the homepage and start typing your legal questions.<br>
⭐ Browse through the latest legal headlines.<br>

⭐ Get personalized recommendations and links to legal resources.
<br>
⭐ Use the chatbot to simulate interactions with a legal assistant.

## 🤝 Contributing

We welcome contributions! Here's how you can help:

- Report bugs via **GitHub Issues**.  
- Submit **pull requests** for new features or improvements.  
- Suggest integrations with new APIs or legal data sources.

---

## 📬 Contact

**Developer**: Tushar Swarnkar  
📧 Twitter: [@tusharswarnkar5](https://twitter.com/tusharswarnkar5)  
💻 GitHub: [Tusharedith](https://github.com/Tusharedith)  
📂 Project Repository: [Legal Navigator](https://github.com/Tusharedith/Legal-Navigator)

---

## 📄 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute it with attribution.

---

## ⭐ Show Your Support

If you found this project helpful, consider giving it a ⭐ on GitHub and sharing it with others!
