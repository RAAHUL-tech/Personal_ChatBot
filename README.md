# Personal_ChatBot

This is a personalized chatbot application developed using langchain to answer queries related to my background. It uses the RAG approach. The vectors are stored in the FAISS vector store.

![Screenshot (536)](https://github.com/user-attachments/assets/18b5ef01-f9e2-4ac4-b1dc-b358a7622a18)

To replicate this application,
1. Clone the repository.
2. Create an API key at https://console.groq.com/keys
3. Create a virtual environment using conda or venv package.
4. Install necessary requirements using `pip install -r requirements.txt`. To avoid configuration issues use Python 3.10 or above.
5. Create a .env file and supply your Groq API key.
6. Upload all your documents to the /docs folder.
7. Finally run the application using `streamlit run app.py`
