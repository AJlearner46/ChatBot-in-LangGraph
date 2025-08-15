# LangGraph Chatbot with Streamlit Interface

---

## 💻 Features

- Chat memory using LangGraph
- Streamed AI responses with typing effect
- Simple UI using Streamlit

---


## Explanation 
- langgraph_backend.py -> Simple langraph agent
- streamlit_frontend.py -> Simple streamlit frontend with streaming response
- streamlit_frontend_threading.py -> added chat history feature in streamlit_frontend.py 

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/AJlearner46/ChatBot-in-LangGraph.git
cd ChatBot-in-LangGraph
```

### 2. Create & activate a virtual env
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Set up your environmental variables
Rename the .env.example file to .env and paste your OpenAI API key:
```bash
OPENAI_API_KEY=your-openai-key-here
```

### 5. Run the chatbot
```bash
streamlit run streamlit_frontend.py
```
Then open the link in your browser (usually http://localhost:8501)


---

