# Gemini-project

# 🔮 Gemini-Powered Chat App using LangChain & Streamlit

An interactive AI chatbot built using **Google Gemini Pro**, **LangChain**, and **Streamlit**. This app allows users to upload documents and ask natural language questions. It uses **FAISS** for vector storage and **Google's Gemini Pro model** for generating intelligent responses.

---

## 🚀 Features

- 🤖 Chat interface powered by **Gemini Pro** via LangChain  
- 📄 Upload documents for question answering  
- 📚 Uses **FAISS** to store and search document embeddings  
- ⚡ Clean and interactive **Streamlit** frontend  
- 🔐 API key-based authentication for Google Generative AI  

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Streamlit** – Web UI
- **LangChain** – LLM framework
- **FAISS** – Vector database
- **Google Gemini Pro** – Language model

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/gemini-langchain-chat.git
cd gemini-langchain-chat
Create a virtual environment

python -m venv myenv
# For Windows
myenv\Scripts\activate
# For Mac/Linux
source myenv/bin/activate
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Set your Google API Key

bash
Copy
Edit
# Windows
set GOOGLE_API_KEY=your_api_key
# Mac/Linux
export GOOGLE_API_KEY=your_api_key
▶️ Run the App
bash
Copy
Edit
streamlit run app.py
📁 Project Structure
bash
Copy
Edit
├── app.py                  # Main Streamlit app
├── faiss_index/            # Stored vector database
├── documents/              # Uploaded files
├── requirements.txt
└── README.md
⚠️ Notes
Only set allow_dangerous_deserialization=True when loading FAISS if you're sure the file is safe.

Ensure that your API key has access to the Generative Language API in Google Cloud Console.

Check your model name — gemini-pro is recommended for use with LangChain.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🙌 Acknowledgments
LangChain

Google Generative AI

Streamlit

FAISS
