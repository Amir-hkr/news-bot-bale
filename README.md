# 📰 NewsHub Bale Bot

<div align="center">

# 🚀 Real-Time Persian News Aggregator for Bale Messenger

### *A modular, lightweight and scalable news bot built with **n8n**, **JavaScript** and the **Bale Bot API**.*

Automatically collects the latest Persian news from multiple trusted news providers, categorizes articles, formats them into clean messages, and delivers them directly to users through an interactive Bale Messenger bot.

---

![n8n](https://img.shields.io/badge/n8n-Automation-EA4B71?style=for-the-badge\&logo=n8n\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![Bale](https://img.shields.io/badge/Bale-Bot-0088CC?style=for-the-badge)
![Workflow](https://img.shields.io/badge/Workflow-Modular-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

⭐ **If you find this project useful, don't forget to Star the repository!**

</div>

---

# 📖 Overview

NewsHub is a fully automated Persian news aggregation bot designed for **Bale Messenger**.

Instead of relying on RSS feeds or third-party APIs, the bot performs **real-time HTML web scraping** from trusted Persian news websites, extracts the latest articles, formats the content, and instantly sends it to users through an interactive Bale interface.

The entire project is implemented visually using **n8n**, making it easy to maintain, extend, and deploy while keeping resource usage extremely low.

---

# ✨ Features

## 📰 News Categories

* 🏛️ Political News
* 🌍 International News
* 💰 Economic News
* ⚽ Sports News
* 📢 Incident News
* 🌱 Health & Medical News
* 🤖 Artificial Intelligence News

---

## ⚡ Core Features

* 🚀 Interactive Bale keyboard
* 📥 Automatic message polling
* 🔄 Duplicate message prevention
* 🌐 Multi-source news aggregation
* 📰 Real-time HTML web scraping
* 📅 Publication date extraction
* 🔗 Original article links
* ⚙️ Modular workflow architecture
* 📱 Mobile-friendly message formatting
* 🧩 Easy to extend with new categories
* 💡 Lightweight execution
* 🔥 No traditional backend required

---

# 🏗️ Architecture

```text
                    User
                      │
                      ▼
             Bale Messenger Bot
                      │
                      ▼
               Get Updates API
                      │
                      ▼
             Parse Incoming Message
                      │
                      ▼
          Duplicate Message Detection
                      │
                      ▼
             Category Switch Router
                      │
      ┌───────────────┼────────────────┐
      │               │                │
      ▼               ▼                ▼
 Political        Sports         AI News
      │               │                │
      ▼               ▼                ▼
 HTTP Request   HTTP Request   HTTP Request
      │               │                │
      ▼               ▼                ▼
 HTML Parsing   HTML Parsing   HTML Parsing
      │               │                │
      └───────────────┼────────────────┘
                      ▼
              JavaScript Processing
                      ▼
             Formatted Bale Message
                      ▼
                 Send Message
```

---

# 🌍 News Sources

The bot currently aggregates articles from trusted Persian news providers.

| Source          | Purpose                      |
| --------------- | ---------------------------- |
| 📰 Shahrekhabar | General News                 |
| 🤖 Hooshio      | Artificial Intelligence News |

Adding a new news source requires only a new workflow branch and extraction logic.

---

# 📱 Example Response

```text
🤖 Latest AI News

1️⃣ Meta disables Muse Image after public criticism.

📅 21 Tir 1405
🔗 https://hooshio.com/...

────────────────────

2️⃣ Claude Cowork is now available on Web & Mobile

📅 21 Tir 1405
🔗 https://hooshio.com/...

────────────────────

3️⃣ DeepSeek develops its own AI chips

📅 19 Tir 1405
🔗 https://hooshio.com/...
```

---

# 🛠 Tech Stack

* n8n
* JavaScript (Code Nodes)
* Bale Bot API
* HTTP Request Nodes
* HTML Extraction
* CSS Selectors
* Regular Expressions
* Data Tables
* Modular Workflow Design

---

# 🚀 Why This Project?

Most messaging bots simply consume RSS feeds or external APIs.

This project takes a different approach.

Instead of depending on third-party services, it directly scrapes trusted Persian news websites, extracts structured information, formats the content, and delivers the latest articles to users in real time.

This architecture provides greater flexibility, allows support for virtually any website, and makes adding new news providers extremely simple.

---

# ⚙️ Installation

1. Clone this repository.

```bash
git clone https://github.com/yourusername/newshub-bale-bot.git
```

2. Import the workflow into n8n.

3. Replace the placeholder values:

```
<YOUR_BALE_BOT_TOKEN>

<YOUR_DATA_TABLE_ID>

<YOUR_PROJECT_ID>
```

4. Activate the workflow.

Done! 🎉

---

# 📂 Project Highlights

✅ Fully visual automation

✅ Modular architecture

✅ Lightweight workflow

✅ Real-time news collection

✅ Multi-category support

✅ Easy maintenance

✅ Easy deployment

✅ Duplicate message protection

✅ Low resource usage

✅ Beginner-friendly workflow

---

# 📈 Roadmap

* [ ] Technology News
* [ ] Cryptocurrency News
* [ ] Science News
* [ ] Entertainment News
* [ ] Personalized subscriptions
* [ ] Scheduled daily news
* [ ] AI-generated summaries
* [ ] Search by keyword
* [ ] Multi-language support
* [ ] More Persian news providers

---

# 🤝 Contributing

Contributions, feature requests and pull requests are always welcome.

Feel free to fork the repository and improve the project.

---

# 📄 License

This project is licensed under the **MIT License**.

---

<div align="center">

### ⭐ Star this repository if you like the project!

Made with ❤️ using **n8n**, **JavaScript** and **Bale Messenger API**

</div>

<p align="center">
  <img src="test-news-bot/test-news-bot.gif" width="800">
</p>
