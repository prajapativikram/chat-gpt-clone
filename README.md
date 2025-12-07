# 💬 ChatGPT Clone — Powered by Gemini API

![GitHub Repo stars](https://img.shields.io/github/stars/prajapativikram/chat-gpt-clone?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/prajapativikram/chat-gpt-clone?style=flat-square)
![License](https://img.shields.io/github/license/prajapativikram/chat-gpt-clone?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

> 🤖 An **AI Chat Application** built using the **Gemini API**, designed to simulate ChatGPT-style conversations with a sleek, responsive UI.

---

## 🚀 Features

- 🧠 **Real-time AI chat** powered by **Google Gemini API**
- 💬 Context-aware, dynamic conversation memory
- ⚡ Fast and responsive UI using modern frontend tech
- 🌗 **Light/Dark mode** toggle for better user experience
- 📱 Fully responsive — works on desktop & mobile
- 🧩 Modular & clean code architecture
- 🔐 Environment variable–based API key management

---

## 🖥️ Tech Stack

| Category | Technologies Used |
|-----------|------------------|
| **Frontend** | HTML5, CSS3, JavaScript / React  |
| **Backend** | Node.js   |
| **AI Model** | Gemini API (Google Generative AI) |
| **Styling** | Tailwind CSS / Custom CSS |
| **Deployment** | Vercel / Netlify / Render / Localhost |

---

## 📸 Demo

> 🎥 **Live Demo:** https://chatbot-rust-mu.vercel.app/


---

## ⚙️ Installation & Setup

Follow these steps to run the project locally 👇

```bash
# 1️⃣ Clone the repository
git clone https://github.com/yourusername/chatgpt-clone.git

# 2️⃣ Move into the project folder
cd chatgpt-clone

# 3️⃣ Install dependencies
npm install

# 4️⃣ Create a .env file and add your Gemini API key
echo "GEMINI_API_KEY=your_api_key_here" > .env

# 5️⃣ Run the development server
npm start


Now open http://localhost:3000 in your browser 🚀

🧠 How It Works

1.The user sends a message via the chat interface.
2.The frontend sends the prompt to the Gemini API endpoint.
3.The Gemini model generates a context-based response.
4.The reply is displayed in the chat interface dynamically.
5.Conversation history is preserved for better flow.


🌟 Example Prompt

You: Write a short poem about AI and creativity.
Gemini: 
"Within the circuits’ silent hum,
Imagination starts to bloom,
Through lines of code, a thought begun,
A spark of art from data’s womb."


🧩 Folder Structure
📂 chatgpt-clone/
├── 📁 public/
├── 📁 src/
│   ├── components/
│   ├── pages/
│   ├── utils/
│   ├── App.js
│   └── index.js
├── .env
├── package.json
└── README.md

🛠️ Environment Variables

Variable	---->   Description
GEMINI_API_KEY	Your Google Gemini API key

🔒 Keep this key secret — never commit it to GitHub.


💡 Future Enhancements

🗣️ Voice-based input & output (speech-to-text + TTS)

🧠 Conversation history storage (localStorage / DB)

🌍 Multilingual support

🧩 Plugin-based architecture for external integrations

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a pull request or issue.

👨‍💻 Author

Vikram Kumar
💼 Software & Frontend Developer



⭐ Show Your Support

If you like this project, give it a star ⭐ on GitHub — it helps others discover it!

“Code. Learn. Build. Repeat.” 🚀

🧠 Fun Interaction (Try in your README viewer!)

💬 Type here what you would ask ChatGPT:
Example: "Explain JavaScript closures with a short example."
Then imagine your clone replying in Gemini’s tone 😄
