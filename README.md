# PaperLi: AI Powered Research Paper Analyzer

An AI-powered research assistant that simplifies academic research papers using Large Language Models (LLMs) and Natural Language Processing (NLP). PaperLi helps users understand complex research content through structured summaries, research analysis, and interactive question answering.

## 🚀 Live Demo

**Try PaperLi here:** [https://paperli.onrender.com/](https://paperli.onrender.com/)

## ✨ Features

- **PDF Research Paper Analysis:** Extract and analyze content from academic papers.
- **Section-Wise Summarization:** Generate summaries of the Abstract, Methodology, Results, and Conclusion.
- **Research Paper Critique:** Generate critical insights into research content.
- **Code and Architecture Analysis:** Explore technical approaches and architectural concepts discussed in papers.
- **Interactive AI Chatbot:** Ask questions about analyzed research papers.
- **Analysis History:** Review previous analyses.
- **Mathematical Equations:** Support for displaying mathematical content.
- **Visualizations:** Present relevant information visually.
- **Downloadable Results:** Export supported analysis outputs.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Backend Framework:** FastAPI
- **LLM:** Google Gemini 2.5 Flash
- **PDF Processing:** PyMuPDF
- **AI/NLP:** Large Language Models, text extraction, summarization, and contextual question answering
- **API:** REST APIs
- **Deployment:** Render

## ⚙️ How It Works

1. Upload a research paper in PDF format.
2. Extract text from the document.
3. Process the extracted content for analysis.
4. Use the configured language model to generate structured insights.
5. Explore summaries, methodology, results, and conclusions.
6. Ask follow-up questions and download supported outputs.

## 💻 Run Locally

### Prerequisites

- Python
- pip
- Google Gemini API key

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_REPOSITORY_FOLDER>
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file and add your API key using the environment variable name expected by the application.

```env
GEMINI_API_KEY=your_gemini_api_key
```

Keep your API key private. Never commit your `.env` file to GitHub.

### 5. Start the Application

For a FastAPI entry point named `main.py`, run:

```bash
uvicorn main:app --reload
```

Open `http://127.0.0.1:8000/docs` to explore the API documentation.

Use the actual entry point and startup command defined in your repository.

## 🎯 Use Cases

- Understanding complex academic research papers.
- Preparing literature reviews.
- Exploring research methodologies and experimental results.
- Reviewing technical approaches and research contributions.
- Asking questions about academic publications.
- Supporting academic learning and research discussions.

## 🔮 Future Enhancements

- Local LLM support through Ollama.
- Retrieval-Augmented Generation (RAG) for improved document-grounded answers.
- Comparative analysis of multiple research papers.
- Improved citation extraction and source references.

## ⚠️ Limitations

AI-generated summaries and critiques may contain inaccuracies. Always verify important findings against the original research paper. Document extraction quality may also vary for scanned PDFs, tables, figures, and complex mathematical notation.

## 👨‍💻 Author

**Sai Kishore Nulu**

- GitHub: [kishore1902](https://github.com/kishore1902)
- LinkedIn: [Sai Kishore Nulu](https://www.linkedin.com/in/kishore-nulu-971411371/)

---

If PaperLi helps you understand research papers more efficiently, try the live application and explore its features.

**Live Application:** [Launch PaperLi](https://paperli.onrender.com/)
