# 🌦️ Weather Advisor

An AI-powered weather assistant that combines real-time weather data with conversational AI to provide human-like weather insights.  
Users can ask natural questions such as *“Do I need an umbrella today in Sydney?”* or *“Is it cold tomorrow in Perth?”*, and the system responds naturally with forecasts and advice.  
This project demonstrates intentional AI prompting, data visualisation, and full-stack integration.

---

## 🌤️ Features

- 🤖 **AI Chatbot** — answers user questions using **Ollama’s LLaMA3** model.  
- ☁️ **Live Weather Data** — sourced from the free [wttr.in](https://wttr.in) API.  
- 📊 **Visual Dashboard** — temperature, humidity, and precipitation charts using **Chart.js**.  
- 💬 **Conversational Interface** — logs previous chat history.  
- 🔒 **Error-Handling** — gracefully manages API or network failures.  
- 🧠 **AI Documentation** — all AI prompts and reflections are saved in the `ai-conversations/` folder.

---

## 🧰 Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend** | Flask (Python) |
| **Frontend** | HTML, CSS, JavaScript |
| **AI Model** | Ollama (LLaMA3) |
| **Weather Data** | wttr.in API |
| **Visualisation** | Chart.js |
| **Version Control** | Git & GitHub |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Sai-Nikhith-Boddu/Weather_Advisor-Boddu-Sai-Nikhith.git
cd Weather_Advisor-Boddu-Sai-Nikhith
pip install -r requirements.txt
ollama pull llama3
flask run
Weather_Advisor/
│
├── ai-conversations/             # AI prompting documentation (5 logs + summary)
│   ├── Conversation1.txt
│   ├── Conversation2.txt
│   ├── Conversation3.txt
│   ├── Conversation4.txt
│   ├── Conversation5.txt
│   
│
├── static/                       # CSS, JS, and image files
├── templates/                    # HTML templates for Flask views
├── weather_data.py               # Fetches and structures weather data
├── weather_advisor.py            # Main Flask application and AI integration
├── requirements.txt              # Python dependencies
├── submission/                   # Reflection and submission checklist
└── README.md                     # Project documentation (this file)

## 🤖 AI Conversations & Prompting Log

This project was developed following **intentional prompting** principles.  
All AI interactions are documented inside the [`ai-conversations/`](./ai-conversations/) folder.

Each file includes:
- The **prompt** provided to the AI model  
- The **AI-generated code or explanation**  
- The **before-and-after implementation** changes  
- A short **reflection** describing what was learned  

These logs show transparency, accountability, and responsible AI usage — fully aligned with the [Weatherwise Template](https://github.com/michaelborck-curtin/weatherwise-template).

---

## 🧾 Submission & Reflection

A comprehensive reflection on the development journey is included in the [`submission/`](./submission/) folder.  
This document outlines:
- The **role of AI tools** in coding, debugging, and design  
- **Key challenges** faced and how they were resolved  
- **Insights gained** from using AI ethically and effectively in software development  

---

## 🪪 License & Acknowledgements

Developed by **Sai-Nikhith Boddu** as part of the Weatherwise project coursework.

**Acknowledgements**
- [Flask](https://flask.palletsprojects.com/) — backend web framework  
- [Ollama](https://ollama.com) — local AI model runtime (LLaMA3)  
- [wttr.in](https://wttr.in) — weather data provider  
- [Chart.js](https://www.chartjs.org) — data visualisation library  
- [Michael Borck’s Weatherwise Template](https://github.com/michaelborck-curtin/weatherwise-template) — structural and academic reference  

---

## 📬 Contact

For feedback or contributions, open an issue or reach out via GitHub:  
**[Sai-Nikhith Boddu](https://github.com/Sai-Nikhith-Boddu)**  
