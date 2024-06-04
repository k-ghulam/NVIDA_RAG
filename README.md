Nvidia NIM (NVIDIA Inference Module) Demo
This repository contains a demo application showcasing the capabilities of the Nvidia NIM (NVIDIA Inference Module) in conjunction with various AI endpoints, document processing, and retrieval techniques.

Features:
Document Embedding: Utilizes Nvidia NIM along with LangChain to embed documents into high-dimensional vector representations.
Question Answering: Enables users to ask questions based on the context provided by the embedded documents and receive accurate responses.
Document Similarity Search: Performs similarity search among documents to find relevant content based on the user's input.
Technologies Used:
Streamlit: Interactive web application framework for building ML and data science tools.
OpenAI: API integration for leveraging AI capabilities, particularly for question answering.
LangChain: AI-powered document processing and retrieval library, incorporating Nvidia NIM and other advanced techniques.
FAISS: Efficient similarity search library for handling high-dimensional vectors.
Setup:
Clone the repository: git clone https://github.com/your-username/nvidia-nim-demo.git
Install dependencies: pip install -r requirements.txt
Set environment variables for API keys:
NVIDIA_API_KEY: Your Nvidia API key for accessing Nvidia NIM.
OPENAI_API_KEY: Your OpenAI API key for utilizing OpenAI's AI capabilities.
Run the Streamlit app: streamlit run app.py
Usage:
Start the Streamlit app by running the command mentioned above.
Use the provided input fields to interact with the demo application:
Enter questions based on the documents loaded.
Trigger document embedding to prepare the vector store.
View answers to questions and perform document similarity searches.
Contributions:
Contributions are welcome! Feel free to open issues for bug reports or feature requests. Pull requests are encouraged for enhancements or fixes.

Credits:
Developed by [Your Name]
Powered by Nvidia NIM, OpenAI, LangChain, and Streamlit.
