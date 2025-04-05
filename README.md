# Building-Local-RAG-Applications-with-LangChain

# Asia Documents Q&A

This project demonstrates building a Question-Answering system over a set of documents related to Asia using LangChain and Gradio. It allows users to ask questions about Asia and receive answers based on the information contained in the provided documents.

## Features

- **Document Loading and Processing:** Loads text documents, splits them into chunks, and creates embeddings using Hugging Face Embeddings.
- **Vector Store:** Uses FAISS to store and search document embeddings for efficient retrieval.
- **Question Answering:** Employs a RetrievalQA chain with a GPT-2 language model to answer user queries based on relevant document chunks.
- **Gradio Interface:** Provides a user-friendly interface for interacting with the Q&A system.

## Installation

1. **Clone the repository:** `` https://github.com/etendra2501/Building-Local-RAG-Applications-with-LangChain.git ``
2. **Install dependencies:** `` pip install langchain langchain_community faiss-cpu sentence-transformers transformers ``

## Usage

1. **Download and extract the dataset:** The code automatically downloads and extracts the necessary documents.
2. **Run the application:** ``https://31b29ec0cb71ebc2a0.gradio.live/ `` 

3. **Access the Gradio interface:** Open the provided URL in your browser.
4. **Enter your question:** Type your question in the input box.
5. **Get the answer:** The answer will be displayed in the output box and Gradio app.

![Alt text](https://raw.githubusercontent.com/etendra2501/Building-Local-RAG-Applications-with-LangChain/main/Image/gradio%20demo%20img.png)


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
