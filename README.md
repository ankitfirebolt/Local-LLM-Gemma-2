# Local-LLM-Gemma-2

## Overview

Local-LLM-Gemmma-2 leverages Generative AI, specifically Google's Gemma 2 (9B parameters), for summarizing query and providing a question-answering system that supports Retrieval-Augmented Generation (RAG) for various document types, including DOCX, PDF, and TXT files. The application runs locally to ensure data privacy and aims to bring the power of LLMs to your laptop.

## Features

- Summarizes notes using Generative AI
- Question answering system with RAG for DOCX, PDF, and TXT files
- Adds relevant references automatically
- Ensures data privacy by running locally
- User-friendly interface

## Installation

### Prerequisites

- Python 3.8 or higher
- Node.js 19.8.1 or higher
- pip

### Setup

1. **Clone the repository**

    ```bash
    git clone https://github.com/ankitfirebolt/Local-LLM-Gemma-2.git
    cd Local-LLM-Gemma-2
    ```

2. **Create and activate a virtual environment**

    ```bash
    python -m venv myenv
    source myenv/bin/activate
    ```

3. **Install Python dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Install Node.js dependencies**

    ```bash
    nvm install v19.8.1
    nvm use v19.8.1
    cd myapp
    npm install
    ```

## Usage

- Download and install Ollama onto the available supported platforms (including Windows Subsystem for Linux)
Fetch available LLM model via

```bash
    ollama pull gemma2
```

- Navigate to the `myapp` directory and run the app client:

    ```bash
    cd client
    npm start
    ```
- Run the backend api controller:

    ```bash
    fastapi dev api_controller.py
    ```
    
- Open your browser and go to `http://localhost:3000` to access the app.

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, please open an issue or contact the repository owner.




## Troubleshooting

pip install langchain fastapi uvicorn

pip install langchain_community tiktoken langchainhub chromadb

pip install -U datasets transformers

pip install -U "huggingface_hub[cli]"
Setup your Access Token: "export HF_TOKEN=<your-access-token>"


pip install "unstructured[all-docs]"

======


