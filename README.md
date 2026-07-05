# 🎥 YouTube RAG (Retrieval-Augmented Generation)

An AI-powered Retrieval-Augmented Generation (RAG) application that allows users to ask questions about a YouTube video. The application extracts the video's transcript, converts it into vector embeddings, stores them in a FAISS vector database, and generates context-aware answers using a Large Language Model (LLM).

---

# 📌 Features

- Extract transcript from any YouTube video
- Automatic text preprocessing
- Intelligent text chunking
- Generate vector embeddings
- Store embeddings in FAISS
- Semantic similarity search
- Context-aware question answering
- Simple Streamlit user interface
- Supports AI, Data Science, Python, SAP, and educational videos

---

# 🚀 Project Workflow

```
           User
             │
             ▼
      Enter YouTube URL
             │
             ▼
    Extract Video Transcript
             │
             ▼
       Clean & Split Text
             │
             ▼
     Generate Embeddings
             │
             ▼
    Store Vectors in FAISS
             │
             ▼
      User Asks Question
             │
             ▼
 Retrieve Relevant Chunks
             │
             ▼
 Large Language Model (LLM)
             │
             ▼
      Generate Response
```

---

# 🛠 Technology Stack

- Python
- LangChain
- FAISS
- OpenAI
- HuggingFace Transformers
- Sentence Transformers
- YouTube Transcript API
- Streamlit
- Dotenv

---

# 📂 Project Structure

```
YouTube-RAG/
│
├── app.py
├── rag.py
├── transcript.py
├── embeddings.py
├── requirements.txt
├── README.md
├── .env
├── vectorstore/
├── data/
├── screenshots/
└── assets/
```

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/youtube-rag.git
```

Go to project folder

```bash
cd youtube-rag
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Using Streamlit

```bash
streamlit run app.py
```

---

# 📚 Required Libraries

```text
langchain
langchain-community
faiss-cpu
transformers
sentence-transformers
youtube-transcript-api
streamlit
python-dotenv
openai
numpy
pandas
tiktoken
```

---

# 💡 How It Works

### Step 1

Enter a YouTube video URL.

### Step 2

The transcript is extracted automatically.

### Step 3

The transcript is cleaned and divided into smaller chunks.

### Step 4

Each chunk is converted into vector embeddings.

### Step 5

Embeddings are stored in a FAISS vector database.

### Step 6

The user asks a question.

### Step 7

The retriever searches the most relevant transcript chunks.

### Step 8

The LLM generates a final answer using the retrieved context.

---

# 🧠 RAG Architecture

```
YouTube Video
      │
      ▼
Transcript Extraction
      │
      ▼
Text Chunking
      │
      ▼
Embedding Model
      │
      ▼
FAISS Vector Store
      │
      ▼
Similarity Search
      │
      ▼
Retrieved Context
      │
      ▼
Large Language Model
      │
      ▼
Final Answer
```

---

# 📈 Advantages

- Fast semantic search
- Accurate context-based answers
- No need to watch long videos
- Easy to scale
- Better than keyword search
- Supports educational content
- Easy integration with Streamlit

---

# ⚠️ Limitations

- Transcript must be available
- Performance depends on embedding quality
- Internet connection required
- Long videos require additional processing time

---

# 🎯 Applications

- Education
- AI Tutorials
- Data Science Learning
- Interview Preparation
- Online Courses
- Research
- Lecture Summarization
- Corporate Training

---

# 🔮 Future Scope

- Multiple YouTube videos
- Chat history
- Voice assistant
- PDF support
- Audio upload
- Image understanding
- Multilingual support
- Cloud deployment
- User authentication

---

# 📊 Sample Output

```
Question:
What is Retrieval-Augmented Generation?

Answer:
Retrieval-Augmented Generation (RAG) combines information retrieval with a Large Language Model. It retrieves relevant information from a vector database before generating an accurate and context-aware response.
```

---

# 📸 Screenshots

Add screenshots here.

```
screenshots/

home.png

output.png

workflow.png
```

---

# 👨‍💻 Author

**Ashwin Kumar**

MBA (Data Analytics)

Python | Machine Learning | Deep Learning | Generative AI | RAG | SQL | Power BI

---

# ⭐ Acknowledgement

Special thanks to the open-source community for providing tools such as LangChain, FAISS, Hugging Face Transformers, Streamlit, and the YouTube Transcript API, which made this project possible.

---

# 📄 License

This project is intended for educational and learning purposes.
