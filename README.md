<h1>Chat PDF with Gemini </h1>  

Welcome to the Chat PDF with Gemini project repository! This project aims to create a web application that allows users to interact with PDF documents using a chat interface powered by Gemini, a conversational AI model. 
<br>

<h1>Overview </h1>
This web application enables users to upload one or multiple PDF documents and ask questions related to the content of these documents. The Gemini model processes the user's questions and provides relevant answers based on the information extracted from the uploaded PDF files. 

<br>

<h1>Features</h1> 
<br>
<h2>PDF Document Processing:</h2> Users can upload PDF documents containing text.
<h2> Natural Language Processing (NLP)</h2> The Gemini model employs NLP techniques to understand user queries.
<h2>Conversational Interface:</h2> Users can ask questions using natural language through a chat interface.
<h2></h2>Intelligent Answers:</h2> Gemini provides intelligent responses based on the content of the uploaded PDF documents.
Usage
<h2>Upload PDF Documents:</h2>: Click on the "Upload PDF Files" button and select one or multiple PDF documents containing the information you want to query.
<h2>Ask Questions:</h2> Type your questions in the chat interface and press Enter to submit. Gemini will process your question and provide an answer based on the content of the uploaded PDF documents. 
<br> 

<h1>Installation</h1>
To run the web application locally, follow these steps:

<h2>Clone the repository:</h2>

<h3>bash</h3>

git clone https://github.com/yourusername/chat-pdf-gemini.git 

<h3>Install dependencies:</h3>

pip install -r requirements.txt 

<h3> create virtual environment in cmd</h3>  

 conda create -p venv python==3.12.1


<h3>Set up Google API Key:</h3>

Create a .env file in the project directory.

Add your Google API Key to the .env file:

GOOGLE_API_KEY=your_google_api_key 

<h3>Run the application:</h3>

streamlit run chat_pdf_gemini.py 

<br> 

<h1>Technologies Used</h1> 

<h2>Streamlit:</h2>Streamlit: The web application framework used for building the user interface.
<h2>PyPDF2:</h2> A Python library for extracting text from PDF documents.
<h2>Google Generative AI: </h2> A model used for text embeddings and generating responses.
<h2>FAISS:</h2> A library for efficient similarity search and clustering of dense vectors. 

<h3>Contributing</h3>
<br>
We welcome contributions from the community! If you'd like to contribute to this project, please follow these guidelines:

<h2>Fork the repository</h2> 
<br> 
Create your feature branch (git checkout -b feature/YourFeature)
Commit your changes (git commit -am 'Add some feature')
Push to the branch (git push origin feature/YourFeature)
Create a new Pull Request
