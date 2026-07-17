# 🤖 Enhanced Q&A Chatbot with OpenAI

An interactive **Question & Answer Chatbot** built using **Streamlit**, **LangChain**, and **OpenAI GPT models**. This application allows users to ask any question and receive AI-generated responses through a simple web interface.

---

## 🚀 Features

- 💬 Interactive chatbot interface
- 🤖 Multiple OpenAI model selection
- 🌡️ Adjustable temperature
- 📝 Adjustable maximum response tokens
- ⚡ Built with LangChain Expression Language (LCEL)
- 📊 LangSmith tracing support
- 🎨 Simple and responsive Streamlit UI

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- OpenAI
- LangSmith
- python-dotenv

---

## 📂 Project Structure

```
Enhanced-QA-Chatbot/
│
├── app.py
├── requirements.txt
├── .env
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/<your-repository>.git
```

```bash
cd <your-repository>
```

---

### 2. Create a Virtual Environment (Optional but Recommended)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Create a `.env` File

Create a file named **`.env`** in the project root directory.

Add the following environment variable:

```env
LANGCHAIN_API_KEY=your_langsmith_api_key
```

> **Note:** Do **NOT** share or commit your `.env` file to GitHub.

---

## 🔐 OpenAI API Key

This application asks for your **OpenAI API Key** inside the Streamlit sidebar during runtime.

No need to store the OpenAI API key inside the `.env` file unless you want to modify the code accordingly.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will be available at:

```
https://basic-chatbot-with-openai-dbaimopdsjczwa6lwbjqxg.streamlit.app/
```

---

## 📸 Application Preview

![App Screenshot](./Screenshot%202026-07-15%20125135.png)
---

## 📦 Requirements

Main libraries used:

- streamlit
- openai
- langchain
- langchain-openai
- python-dotenv

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🌐 OpenAI Models Supported

- GPT-4o
- GPT-4 Turbo
- GPT-4

---

## 📊 LangSmith Tracking

This project supports **LangSmith** for monitoring and tracing LangChain executions.

To enable tracing, add your LangSmith API key inside the `.env` file.

```env
LANGCHAIN_API_KEY=your_langsmith_api_key
```

Tracing is enabled using:

```python
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=Q&A Chatbot with OpenAI
```

---

## 📄 License

This project is intended for educational purposes.

---

## 👨‍💻 Author

**Atmuri Satya Prakash**

GitHub: https://github.com/Atmuri-SatyaPrakash
