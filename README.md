# Document Processing and Question & Answer Project

It is an example that performs text extraction, vectorization and querying from PDF files using angChain and Hugging Face models.
The project is designed to process complex documents and extract information using specialized language models and text processing tools.

## Features

- **PDF Processing:** LangChain's `PyPDFLoader` component loads documents and breaks them into text fragments.
  
- Text Fragmentation:** Text is fragmented with specific character boundaries and overlap parameters, simplifying management and processing.
  
- Vectorization and Similarity Search:** Text fragments are converted into vectors using Hugging Face models. These vectors are stored in a database called `Chroma` and used for similarity searches.

- Question-Answering:** The Hugging Face language model, which is designed to directly answer any question, is used. Document fragments are scanned and the relevant text context is used to find the most appropriate answer to a given question.

## Installation

1. **Requirements**
   - Python 3.x
   - Pip

2. **Installation**
   ```bash
   git clone https://github.com/badelmay/proje.git
   cd project
   pip install -r requirements.txt
