# ChatPDF_AI
The MultiPDF Chat App is a Python application designed to facilitate interactive conversations with multiple PDF documents. By leveraging advanced language models, the app allows you to ask questions in natural language and receive relevant responses based on the content within the PDFs. It's important to note that the application will only respond to queries directly related to the information contained in the loaded documents. This project highlights how to leverage a ChromaDB vector store in a Langchain pipeline to create a chat with a Pdf application. You can load in a pdf based document and use it alongside an LLM without fine-tuning.

# Working

The application follows these steps to provide responses to your questions:

1. PDF Loading: The app reads multiple PDF documents and extracts their text content.

2. Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

3. Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

4. Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

5. Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.
