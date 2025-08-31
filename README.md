# 📚 Chat With Multiple PDFs  

Ask questions across multiple PDF files at once — with smart, context-aware answers powered by Google’s **Gemini Pro** large language model.

---

## 🚀 Overview

This project lets you:
- Upload multiple PDF documents.
- Parse, split, and embed their contents.
- Store embeddings for similarity search.
- Ask natural language questions.
- Get answers directly from your PDFs using **Google Gemini Pro**.

---

## 🧩 Tech Stack

- **Python 3.8+**
- **LangChain** — for chaining PDF loaders, embedding, and retrieval.
- **Google Gemini Pro** — as the LLM to generate answers.
- **PyPDF2**  — for parsing PDF files.
- **FAISS**  — for vector store.
- **dotenv** — to manage API keys securely.

---

## 📂 Project Structure

```plaintext
AskAnything-QueryMultiplePDFs-with-Gemini-Pro/
├── app.py             # Main script to run the chat system
├── requirements.txt   # Python dependencies
├── uploads/           # Folder for uploaded PDFs
├── .env               # Your API keys (add manually)
├── README.md          # Project documentation


## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository  
Clone the repository and change into the project directory:

git clone https://github.com/krgau020/AskAnything-QueryMultiplePDFs-with-Gemini-Pro.git  
cd Chat_With_Multiple_Pdf_GOOGLE_GEMINI_PRO

---

### 2️⃣ Create a Virtual Environment  
It’s recommended to create and activate a virtual environment.

Create:  
python -m venv venv

Activate it:  
**Linux/Mac:**  
source venv/bin/activate

**Windows:**  
venv\Scripts\activate

---

### 3️⃣ Install Dependencies  
Install the required Python packages:

pip install -r requirements.txt

---

### 4️⃣ Add Your Google Gemini Pro API Key  
Create a `.env` file in the project root and add your API key like this:

GOOGLE_API_KEY=YOUR_GEMINI_API_KEY

---

## 🚀 Usage  
Run the app:

python app.py

**How it works:**  
1. Upload one or more PDF files when prompted.  
2. Enter your question in natural language.  
3. The app will:  
   - Load and split the PDFs  
   - Create embeddings  
   - Find relevant chunks  
   - Query Gemini Pro  
   - Return an answer grounded in your files

---

## ✅ Requirements  
- Python 3.8+  
- Google Gemini Pro API key

---

## 📈 Example Result  
Upload multiple research papers → ask a detailed question → get an accurate answer that directly references your uploaded PDFs.


