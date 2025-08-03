RAG PIPELINE - INSTALLATION & USAGE GUIDE
=========================================

🔧 INSTALLATION STEPS
---------------------

1. Clone the repository
   ---------------------
   git clone https://github.com/yourusername/rag-pipeline.git
   cd rag-pipeline

2. (Optional) Create and activate a virtual environment
   ----------------------------------------------------
   On Windows:
   python -m venv venv
   venv\Scripts\activate

   On macOS/Linux:
   python3 -m venv venv
   source venv/bin/activate

3. Install required Python packages
   --------------------------------
   If you have requirements.txt:
   pip install -r requirements.txt

   Or manually install the core dependencies:
   pip install langchain faiss-cpu tiktoken chromadb openai ipywidgets jupyter

4. (Optional) Install additional tools for local models
   ----------------------------------------------------
   For HuggingFace or Ollama:
   pip install langchain-huggingface

   If using Ollama, install it from: https://ollama.com


▶️ HOW TO RUN THE NOTEBOOK
--------------------------

1. Launch Jupyter Notebook
   ------------------------
   jupyter notebook

2. Open 'Rag_Pipeline.ipynb' in your browser.

3. Set up your API keys and document paths as required.

4. Run all cells in order:
   ------------------------
   Use the option: Kernel > Restart & Run All


📁 FOLDER STRUCTURE
-------------------
rag-pipeline/
│
├── Rag_Pipeline.ipynb        # Main notebook for building the RAG pipeline
├── data/                     # Folder to store your documents or files (create this if needed)
├── vectorstore/              # FAISS index files (auto-created after running the notebook)
├── README.md                 # This file
└── requirements.txt          # Python package dependencies


📦 REQUIREMENTS.TXT CONTENT
---------------------------
langchain>=0.1.14
faiss-cpu>=1.7.4
tiktoken
chromadb
openai
ipywidgets
jupyter
langchain-huggingface

(If using Ollama, make sure it's installed and running: https://ollama.com)
