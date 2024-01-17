
# AnnualReport Analyzer RAG

## Overview

AnnualReport-Analyzer-RAG is a Python script designed to perform analysis and answer queries related to the Annual Report of any company. The script showcases an example using Infosys Annual Report, but it is versatile and can be applied to analyze reports from any company. It utilizes the Retrieval Augmented Generation (RAG) approach with the LangChain library and various other tools for document loading, embeddings, and evaluation.

## Features

- **OpenAI Integration:** Leverages the OpenAI language model for text generation.
- **Chroma Vector Store:** Utilizes Chroma vector store for document storage and retrieval.
- **VectorStore Toolkit:** Implements the VectorStore Toolkit from LangChain for seamless integration.
- **Evaluation Metrics:** Evaluates model performance using metrics such as faithfulness, answer relevancy, and context relevancy.

## Prerequisites

- Python 3.6 or higher
- LangChain 
- ChromaDB 
- OpenAI 
- PyPDF 
- Tiktoken 
- RAGAS 

## Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/infosys-annual-report-analysis.git
    cd infosys-annual-report-analysis
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up environment variables:

    - Set `OPENAI_API_KEY` to your OpenAI API key.

4. Run the script:

    ```bash
    python infosys_ar_23.py
    ```

5. Enter the queries related to the Infosys Annual Report when prompted.

## Evaluation Metrics

The script uses metrics from RAGAS for evaluation:

- **Faithfulness Score:** Measures the faithfulness of the generated response to the source document.
- **Answer Relevancy Score:** Assesses the relevance of the generated answer to the query.
- **Context Relevancy Score:** Evaluates how well the generated context aligns with the source document.

## Example Usage

```bash
python infosys_ar_23.py
```

Enter your queries related to the Infosys Annual Report when prompted.

## License

This project is licensed under the [MIT License](LICENSE).

---
