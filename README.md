
# 💬 JKNNS ICT Chatbot (AI-Powered FAQ Assistant)

This chatbot answers ICT-related questions for the Negeri Sembilan State Health Department (JKNNS), powered by OpenAI and Flask.

## 📦 How to Run Locally

```bash
git clone https://github.com/your-username/jknns-chatbot.git
cd jknns-chatbot
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
echo OPENAI_API_KEY=your-key-here > .env
python app.py
```

Visit: http://localhost:5000

## 🟢 Deploy on Render

1. Connect your GitHub repo to Render
2. Add environment variable: `OPENAI_API_KEY`
3. Build command: `pip install -r requirements.txt`
4. Start command: `python app.py`
