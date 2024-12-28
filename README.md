# Text Summarization Using LangChain

This project demonstrates various methods for summarizing text and speeches using LangChain and OpenAI's GPT-3.5 Turbo. It supports basic prompt-based summarization, advanced summarization techniques like map-reduce, and custom workflows for large documents, including PDFs.

---

## Features

1. **Basic Prompt Summarization**:
   - Summarizes text or speeches using simple prompts.
   - Allows summaries to be translated into other languages.

2. **Advanced Summarization**:
   - **Map-Reduce**: Summarizes large documents by splitting them into chunks, summarizing each, and combining the results.
   - **Refine Chain**: Enhances summaries iteratively for better accuracy and clarity.
   - **Custom Prompts**: Tailored prompts for specific summary requirements.

3. **PDF Summarization**:
   - Extracts text from PDF files.
   - Processes and summarizes text directly from documents.

4. **Integration with OpenAI and LangChain**:
   - Uses `ChatOpenAI` for generating summaries.
   - Employs `PromptTemplate` for customizable summary prompts.
   - Handles large documents with efficient chunking and processing.

---

## Technologies Used

- **LangChain**: Provides structured workflows for LLM-based text processing.
- **OpenAI API**: Powers text summarization with GPT-3.5 Turbo.
- **PyPDF2**: Extracts text from PDF files for summarization.

---

## Setup Instructions

### Prerequisites

- Python 3.8 or later installed on your system.
- OpenAI API key for accessing GPT models.

### Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
