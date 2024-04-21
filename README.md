# Chat with PDF

This Streamlit application allows users to interact with PDF documents in a unique and engaging way. Utilizing Azure Form Recognizer for extracting text and table data, storing and indexing this information in ChromaDB, and enabling interactive querying with the assistance of OpenAI's GPT-4, this application showcases the integration of modern APIs and machine learning technologies to enhance document management and interaction.

## Features

- **PDF Upload**: Users can upload PDF files which the system will process.
- **Text and Table Extraction**: The application uses Azure Form Recognizer to automatically extract text and table data from the uploaded PDFs.
- **Interactive Chat Interface**: Users can ask questions about the document content, and the system, powered by OpenAI's GPT-4, responds in a conversational manner.

## Technologies Used

### Streamlit

Streamlit is an open-source Python library used for creating and sharing beautiful, custom web apps for machine learning and data science. In this project, Streamlit is used to build the entire web application, from file upload to displaying the chat interface.

### Azure Form Recognizer

Azure Form Recognizer is a cloud-based cognitive service that uses machine learning technology to identify, and extract key-value pairs and table data from form documents. It transforms the PDF documents into usable data.

### ChromaDB

ChromaDB is a vector database designed for fast and efficient similarity search of data in high dimensional space. In this application, ChromaDB is used to store and retrieve document data that has been transformed into embeddings. This facilitates efficient querying of document contents based on semantic similarity.

### OpenAI GPT-4

OpenAI's GPT-4 is a state-of-the-art language model capable of understanding and generating human-like text based on the input it is given. In this application, GPT-4 is used to generate responses to user queries, enabling an interactive chat feature where the application can answer questions about the document's content.

## Setup and Installation

   git clone https://github.com/yourrepository/chat-with-pdf.git

   pip install streamlit azure-ai-formrecognizer chromadb openai

   streamlit run app.py


   ![Screenshot 2024-04-21 at 5 08 28 PM](https://github.com/anudeep2804/chat-with-pdf/assets/68229062/f60cb721-b962-4de8-8bfa-c9ea3dd929ea)


