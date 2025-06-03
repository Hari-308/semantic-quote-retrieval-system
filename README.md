# semantic-quote-retrieval-system
This project is a lightweight semantic search engine for quotes using FAISS and Sentence Transformers, served via a Streamlit app.

🚀 Features
Semantic search using all-MiniLM-L6-v2

FAISS for fast similarity lookup

Interactive Streamlit frontend

Auto-parses quote tags and handles missing data

📁 Files
main.py: Loads data, builds embeddings, launches app

English Quotes.csv: Dataset with quotes, authors, and tags

temp_app.py: Auto-generated Streamlit app

⚙️ Requirements
Install with:

bash
Copy
Edit
pip install pandas numpy faiss-cpu sentence-transformers streamlit torch
▶️ Run
bash
Copy
Edit
python main.py
Visit the printed localhost link to use the app.

🧠 Example Queries
"failure and resilience"

"wisdom about time"

💡 Name Ideas
QuoteRAG, Echoes of Wisdom, SemanticQuote
