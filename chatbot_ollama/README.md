# 🤖 AI Chatbot with Mistral (Ollama)

This project is a hands-on experiment where I built a functional AI chatbot from scratch, using a local large language model.

The goal was simple: learn by doing, step outside my comfort zone, and understand how modern AI tools can be integrated into a real web application.

---

## 👀 Overview

This chatbot is powered by a Mistral model running locally via Ollama, and connected to a web interface using JavaScript.

The project demonstrates how to:
- Run an AI model locally (no external API)
- Connect a frontend interface to a local AI server
- Send and handle user prompts in real time
- Build a working chatbot even with limited JavaScript experience

---

## ⚙️ Tech Stack

- **Mistral (LLM)** – language model used for responses  
- **Ollama** – local model hosting  
- **JavaScript (frontend)** – chatbot interface and API calls  
- **HTML/CSS** – basic UI  

---

## ✨ Features

- Local AI chatbot (no cloud dependency)  
- Real-time interaction with the model  
- Simple and lightweight web interface  
- Custom prompt handling  

---

## 💡 How It Works

1. The Mistral model runs locally via Ollama  
2. The web app sends user input to the model using its local IP  
3. The model processes the prompt and returns a response  
4. The response is displayed in the chatbot interface  

---

## 🚀 Usage

### 1. Clone the repository

```
git clone git@github.com:Louis-Cagnion/Artificial-Intelligence.git
cd Artificial-Intelligence
```

### 2. Start Ollama with Mistral

Make sure Ollama is installed, then run:

```
ollama run mistral
```

### 3. Run the frontend

Open the HTML/JS project in your browser (or use a local server).

---

## 📈 Next Improvements

- Improve UI/UX design  
- Optimize prompt engineering  
- Add conversation memory  
- Enhance performance and response handling  

---

## 🧑‍💻 Author

Created and maintained by Louis-Cagnion  

---

## 💬 Feedback

Feel free to open an issue, suggest improvements, or reach out if you want to discuss the project.