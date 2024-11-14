# 📄 Chatbot with Llama 3.2 and Qdrant


This project is a chatbot application that utilizes the Llama 3.2 language model and Qdrant vector database to provide a conversational interface for users. The chatbot is designed to understand and respond to user input, leveraging the power of Llama 3.2's natural language processing capabilities and Qdrant's efficient vector search.

![App Screenshot](https://i.ibb.co/kQ1CxSf/2024-11-13-01-39.png)

## 🛠️ Features

- **📂 Upload Documents**: Easily upload and preview your PDF documents within the app.
- **🧠 Create Embeddings**: Generate embeddings for your documents to enable efficient search and retrieval.
- **🤖 Chatbot Interface**: Interact with your documents using a smart chatbot that leverages the created embeddings.
- **🌟 User-Friendly Interface**: Enjoy a sleek and intuitive UI with emojis and responsive design for enhanced user experience.

## 🖥️ Tech Stack

This App leverages a combination of cutting-edge technologies to deliver a seamless and efficient user experience. Here's a breakdown of the technologies and tools used:

- **[LangChain](https://langchain.readthedocs.io/)**: Utilized as the orchestration framework to manage the flow between different components, including embeddings creation, vector storage, and chatbot interactions.
  
- **[Unstructured](https://github.com/Unstructured-IO/unstructured)**: Employed for robust PDF processing, enabling the extraction and preprocessing of text from uploaded PDF documents.
  
- **[BGE Embeddings from HuggingFace](https://huggingface.co/BAAI/bge-small-en)**: Used to generate high-quality embeddings for the processed documents, facilitating effective semantic search and retrieval.
  
- **[Qdrant](https://qdrant.tech/)**: A vector database, responsible for storing and managing the generated embeddings for fast and scalable retrieval.
  
- **[LLaMA 3.2 via Ollama](https://ollama.com/)**: language model to power the chatbot, providing intelligent and context-aware responses based on the document embeddings.
  
- **[Streamlit](https://streamlit.io/)**: The core framework for building the interactive web application, offering an intuitive interface for users to upload documents, create embeddings, and interact with the chatbot.


## 🚀 Getting Started

Follow these instructions to set up and run the project App on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/AABENZ/CHAT.git

2. Create a Virtual Environment

You can either use Python’s venv or Anaconda to create a virtual environment for managing dependencies.

Option 1: Using venv

On Windows:

python -m venv venv
venv\Scripts\activate

Option 2: Using Anaconda

Follow these steps to create a virtual environment using Anaconda:

	1.	Open the Anaconda Prompt.
	2.	Create a new environment:

conda create --name project1 python=3.9

(Replace project1 with your preferred environment name if desired).

	3.	Activate the newly created environment:

conda activate project1

3. Install Dependencies

Once the environment is set up (whether venv or Conda), install the required dependencies using requirements.txt:

pip install -r requirements.txt

4. Run the App

Start the Streamlit app using the following command:

streamlit run app.py

Note: If your main application file is named differently, replace app.py with your actual file name (e.g., main.py).

This command will launch the app in your default web browser. If it doesn’t open automatically, navigate to the URL provided in the terminal (usually http://localhost:8501).
```

### 🔗 Useful Links


•	Streamlit Documentation: https://docs.streamlit.io/

•	LangChain Documentation: https://langchain.readthedocs.io/

•	Qdrant Documentation: https://qdrant.tech/documentation/

•	ChatOllama Documentation: https://github.com/langchain-ai/langchain-llms#ollama
