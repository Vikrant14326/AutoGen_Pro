# DEMO OF PROJECT

https://github.com/user-attachments/assets/75aa1f48-a256-4f03-b7d1-7c12b40aa8bf

# 📚 Virtual Research Assistant

## 🔍 AI-Powered Research Paper Finder

The **Virtual Research Assistant** is a **Streamlit-based AI tool** that helps users find the **top 5 research papers** on any given topic. It retrieves papers from **ArXiv and Google Scholar**, summarizes them, and provides **advantages and disadvantages** for each paper.

---

## 🚀 Features

✔️ **Fetches Top 5 Research Papers** 📄  
✔️ **Provides Direct Links** to Papers 🔗  
✔️ **Summarizes Each Paper** Concisely 📝  
✔️ **Lists Advantages & Disadvantages** 📌  
✔️ **User-Friendly Streamlit Interface** 🎨  

---

## 🛠️ Tech Stack

- **LangChain** 🧠 (LLM-based workflows)  
- **Streamlit** 🎨 (Web Interface)  
- **Autogen** 🤖 (Agent-based automation)  
- **Scholarly** 📚 (Google Scholar API)  
- **Python-dotenv** 🔐 (Environment variable management)  
- **Transformers** 🤗 (Tokenization support)  
- **ArXiv API** 🔍 (Research paper retrieval)  

---

## 📂 Project Structure

```
📂 Virtual-Research-Assistant
├── 📄 app.py             # Streamlit UI
├── 📄 agents.py          # AI Agents for summarization & analysis
├── 📄 data_loader.py     # Research paper retrieval from ArXiv & Google Scholar
├── 📄 requirements.txt   # Dependencies
├── 📄 .env               # API keys (Add your own)
├── 📄 README.md          # Documentation
```

---

## ⚡ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Virtual-Research-Assistant.git
cd Virtual-Research-Assistant
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Set Up API Keys
Create a `.env` file and add:
```ini
GROQ_API_KEY=your_api_key_here
```

### 4️⃣ Run the App
```bash
streamlit run app.py
```

---

## 🎯 How It Works

1️⃣ **Enter a research topic** in the text field.  
2️⃣ **Click "Search"** to fetch papers.  
3️⃣ The app retrieves, summarizes, and analyzes the top research papers.  
4️⃣ **View links, summaries, and pros/cons** instantly!

---

## 📌 Example Output

🔹 **Title:** Deep Learning for NLP  
🔹 **🔗 Link:** [Read Paper](#)  
🔹 **Summary:** This paper explores how deep learning models transform NLP tasks...  

**Advantages:**
✔️ Improves accuracy in NLP models  
✔️ Scalable for large datasets  

**Disadvantages:**
❌ Requires high computational power  
❌ Needs large amounts of data  

---

Enjoy seamless research with **Virtual Research Assistant**! 🚀
