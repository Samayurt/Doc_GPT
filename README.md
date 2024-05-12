# Doc_GPT
LLM_PROJECT

**Streamlit Application Setup:**

The code sets up a Streamlit application for interacting with multiple PDF documents.

Users can ask questions about the uploaded PDFs and receive responses.


**PDF Text Extraction:**

The get_pdf_text function extracts text from uploaded PDF files using PyPDF2.

It reads each page of the PDFs and concatenates the text.


**Text Chunking:**

The get_text_chunks function splits the extracted text into smaller chunks for processing.

It uses a CharacterTextSplitter to divide the text into manageable segments.


**Vector Store Creation:**

The get_vectorstore function creates a vector store from the text chunks.

It utilizes SentenceTransformer embeddings and FAISS for efficient storage and retrieval.



**Conversation Chain Setup:**

The get_conversation_chain function establishes a conversational retrieval chain for chat interactions.

It uses CTransformers to create a language model and memory for conversation history.


**User Input Handling:**

The handle_userinput function processes user questions and generates responses.

It interacts with the conversation chain to provide chat-like interactions.



**CSS Styling:**

The CSS styling defines the appearance of the chat messages in the Streamlit interface.

It customizes the background color and layout of the chat messages.



**Main Function Execution:**

The main function orchestrates the Streamlit app's functionality and user interactions.

It manages the upload and processing of PDF documents, chat responses, and user input handling.
