# 💬 FinPal Chatbot

FinPal is an AI-powered financial assistant chatbot built with **Python**, **Streamlit**, and **Hugging Face Transformers**.  
It provides interactive financial insights and answers user queries in a simple web interface.

---

## 📂 Project Structure
```
finpal_chatbot/
│── streamlit_app.py       # Main Streamlit application
│── prompts.py             # Predefined chatbot prompts
│── requirements.txt       # Project dependencies
│── .env.sample.txt        # Sample environment variables
│── .gitignore             # Ignored files for Git
```

---

## ⚡ Features
- AI-powered responses using **Hugging Face Transformers**  
- Simple and interactive **Streamlit UI**  
- Configurable environment variables (`.env`)  
- Modular prompt management  

---

## 🛠️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/finpal_chatbot.git
cd finpal_chatbot
```

### 2. Create and activate virtual environment
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure environment variables
Copy the sample file and update values:
```bash
cp .env.sample.txt .env
```

Edit `.env` with your keys (e.g., Hugging Face API key, etc.).

---

## ▶️ Running the Application
Run the Streamlit app with:
```bash
streamlit run streamlit_app.py
```

The app will start locally (default: `http://localhost:8501`).

---

## 🧑‍💻 Technologies Used
- **Python 3.x**
- **Streamlit**
- **Hugging Face Transformers**
- **dotenv**

---

## 🤝 Contribution
1. Fork the repo  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit changes (`git commit -m "Added feature"`)  
4. Push to branch (`git push origin feature-name`)  
5. Create a Pull Request  


---

## ✨ Author
Developed by **1.P.DINESH
2.SANTHOSH
3.NARENDER
** 🚀
