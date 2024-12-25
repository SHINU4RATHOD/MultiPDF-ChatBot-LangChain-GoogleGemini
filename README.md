# MultiPDF-ChatBot-LangChain-GoogleGemini

**Transform how you interact with your documents!** This project enables users to upload multiple PDF files, process the content, and ask questions to extract valuable insights. Powered by LangChain, Google Gemini Pro, and FAISS for efficient text processing, embedding, and conversational AI.
![image](https://github.com/user-attachments/assets/fc16729c-e826-4b01-8c85-e8d271f1b4ec)



---

## Features

- 📄 **Multi-PDF Support**: Upload and interact with multiple PDF files simultaneously.
- 🤖 **AI-Powered Answers**: Get precise answers using Google Gemini Pro.
- 🔍 **Vector Search**: Efficiently retrieve relevant document sections via FAISS.
- 🧠 **Customizable Chain**: Tailored prompt templates for detailed responses.
- 🛠 **Easy-to-Use UI**: Streamlit-based interface for seamless interaction.

---

## How It Works

1. **Upload PDFs**: Users upload one or more PDF files via a user-friendly interface.
2. **Text Extraction**: Extract content from the uploaded files using `PyPDF2`.
3. **Text Chunking**: Split large documents into manageable chunks for better processing.
4. **Vectorization**: Create embeddings with Google Generative AI and store them using FAISS.
5. **Conversational Chain**: Generate context-aware answers to user queries using LangChain's QA Chain.
6. **Query Execution**: Users can input questions to interact with their documents.

---

## Technologies Used

- **LangChain**: Framework for building applications powered by language models.
- **Google Gemini Pro**: Next-gen AI for embeddings and conversational responses.
- **FAISS**: Vector similarity search for efficient document retrieval.
- **Streamlit**: Simple UI framework for deploying Python applications.
- **PyPDF2**: PDF file reading and processing.
- **dotenv**: Manage environment variables securely.

---

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- A Google API key for Gemini Pro
- Git installed on your machine

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/SHINU4RATHOD/Chat-MultiPDF-LangChain-Gemini.git
   cd Chat-MultiPDF-LangChain-Gemini
   
# workflow

### STEP 01- Create a conda environment after opening the repository
```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE-GEMINI credentials as follows:

```ini
GOOGLE_GEMINI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

# Run app file 
```bash
streamlit run app.py
```
