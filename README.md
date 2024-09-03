# InfoRover : AI-Powered PDF Organizer and Knowledge Retrieval Bot

## Overview

**Inforover** is designed to provide comprehensive insights into PDF documents by extracting text, images, and links. The tool enhances document analysis through advanced features, including granular text splitting, semantic understanding, and efficient similarity searches.

## Key Features

- **PDF Content Extraction**: 
  - Extracts and processes text, images, and links from PDF files, offering a detailed overview of document content.

- **Character Text Splitter (Langchain)**: 
  - Uses Langchain to split text at the character level, improving the detail and accuracy of text analysis.

- **OpenAI Embeddings**: 
  - Applies OpenAI embeddings to capture and represent the semantic meaning of the extracted text, enabling sophisticated analysis and query handling.

- **FAISS Operations**: 
  - Integrates FAISS for rapid similarity searches, allowing users to efficiently locate relevant information based on their input queries.

- **User Interaction**: 
  - Provides an intuitive interface for users to input prompts and receive tailored outputs based on similarity searches.

## Dependencies

- **PyPDF2**: 
  - For handling PDF files and extracting text and images.

- **Langchain**: 
  - For advanced text processing and character-level splitting.

- **OpenAI**: 
  - For generating embeddings and performing semantic analysis.

- **FAISS**: 
  - For high-performance similarity searches.


## Usage
- Upload your PDF file using the provided interface or command-line tool.
- The tool will automatically extract text, images, and links from the document.
- Use the prompt feature to query specific information or generate insights based on the document content.


## License
This project is licensed under the MIT License.

