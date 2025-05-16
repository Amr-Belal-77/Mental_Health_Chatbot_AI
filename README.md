```markdown
# 💙 Mental Health AI Chatbot 🤖

A **Deep Learning Powered Chatbot** for Mental Health Support.  
This project uses **Seq2Seq (Encoder-Decoder with Attention) + LSTM** to generate empathetic, human-like responses to users expressing emotions or mental health situations.

> 🎯 Our mission is to build an AI that listens, understands, and supports users emotionally.

---

## 🌟 Features
- 🧠 AI-powered response generation.
- 🔥 Trained on **Empathetic Dialogues Dataset**.
- ⚡ Uses **Attention mechanism** to improve response quality.
- 🖥 Simple and clean **Flask API** ready to plug into any frontend (Web, Mobile, Desktop).
- 💬 Example-ready frontend (HTML/JS) to test the bot visually.

---

## 💻 Project Structure
```

Mental-Health-Chatbot-AI/
├── API/
│   ├── app.py                  # Flask API backend
│   ├── chatbot\_response.keras  # Trained chatbot model
│   ├── tokenizer.pkl            # Trained tokenizer
│   ├── requirements.txt         # Python dependencies
│   ├── test\_request.py          # Quick API test script
│   └── README.md                # Project documentation
└── frontend/
├── index.html
├── style.css
└── main.js

````

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/Mental-Health-Chatbot-AI.git
cd Mental-Health-Chatbot-AI/API
````

### 2. Install the dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the API server

```bash
python app.py
```

API will be live at:

```
http://localhost:5000/chat
```

---

## 🔗 API Usage Example

```json
POST /chat
{
  "message": "I am feeling down today"
}
```

Response:

```json
{
  "reply": "I'm here for you. It's okay to feel that way sometimes."
}
```

---

## 🧪 Quick Test

Run the included Python test script:

```bash
python test_request.py
```

---

## 💡 Technical Stack

| Component          | Technology                 |
| ------------------ | -------------------------- |
| API Backend        | Flask (Python)             |
| Model Architecture | Seq2Seq (LSTM + Attention) |
| Tokenizer          | Keras Tokenizer            |
| Frontend Example   | Vanilla JS + HTML + CSS    |

---

## 🎓 Model Details

* **Encoder-Decoder architecture with Attention**.
* Trained on **Empathetic Dialogues Dataset**.
* Uses **GloVe 300d embeddings** for rich semantic understanding.
* Handles sequence generation using `TensorFlow + Keras`.

---

## ⚙ Requirements

* Flask
* TensorFlow
* Numpy
* Pickle
* Requests (for testing)

> Full list in `requirements.txt`

---

## 🚫 Disclaimer

This chatbot is **NOT a replacement for real mental health professionals**.
It is intended for **educational and research purposes only**.

---

## ✨ Future Improvements (Ideas)

* Migrate to **Transformers (e.g., T5, GPT)**.
* Add multi-language support.
* WebSocket support for real-time chat.
* Improve UI with React or Flutter.

---

## 📄 License

MIT License

---

## 🤝 Contributing

Contributions are welcome!
Please fork the repo and submit a pull request.

---

## 🚀 About

with Medivators team
