# Chat with PDF using Gemini and LangChain

This is a Streamlit app that allows users to upload multiple PDF files and ask questions based on their content. It uses **Gemini (Google Generative AI)** for answering queries and **FAISS** for semantic search.

## 🚀 Features
- Upload multiple PDFs
- Text extraction using PyPDF2
- Chunking and embedding with LangChain + FAISS
- Gemini API for question answering

## 🔐 Setup Instructions

1. Clone the repo and install dependencies:
\`\`\`
pip install -r requirements.txt
\`\`\`

2. Create a \`.env\` file in the root:
\`\`\`
GEMINI_API_KEY=your_gemini_api_key
# Option A (local):
# Place your service_account.json in the root directory

# Option B (Streamlit / cloud):
SERVICE_ACCOUNT_JSON={\"type\":\"service_account\",...}
\`\`\`

3. Run the app:
\`\`\`
streamlit run app.py
\`\`\`

## ✅ Notes
- \`service_account.json\` is required but must NOT be pushed to GitHub.
- Add \`.env\`, \`service_account.json\`, and \`service_account_temp.json\` to \`.gitignore\`


