# Finance LLM 13B Model API

## Overview
This is a FastAPI application that serves as an API endpoint for the Finance LLM 13B model. The API allows users to get answers from the Finance LLM 13B model.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/metriccoders/chatgpt_finance_backend.git
    ```

2. Navigate to the project directory:
    ```bash
    cd chatgpt_finance_backend
    ```
## Usage
1. Install all the required dependencies: llama_cpp, fastapi, uvicorn and pydantic.
2. Download the Finance-llm-13b.Q2_K.gguf model from https://huggingface.co/TheBloke/finance-LLM-13B-GGUF/tree/main
3. Update the path to model in the code.
4. Start the server:
    ```bash
    uvicorn main:app --reload
    ```
## License
MIT
