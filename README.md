# Enhanced Q&A Chatbot With Ollama 

<div align="center">

  <img src="https://github.com/user-attachments/assets/a8bba8ce-ee6d-4ed8-9046-a56b398b1704" alt="Description of the image" width="200" height="200"/>
    <img src="https://github.com/user-attachments/assets/f36cda5e-097d-484f-9cbc-e5b357a794d0" alt="Description of the image" width="200" height="200"/>
  <img src="https://github.com/user-attachments/assets/7de5c03c-79ba-4bfa-ba28-bedd6b28673f" alt="Image 2" width="200" height="200"/>

</div>


This project is a Q&A chatbot powered by **Streamlit** and **Ollama** models, allowing users to ask questions and receive helpful responses. The chatbot provides an interactive interface and allows for model selection and response customization.

## Features
- **User-friendly Interface**: A simple web interface where users can ask any question.
- **Model Selection**: Choose between open-source models such as `llama3.1` and `gemma2:2b`.
- **Response Customization**: Adjust parameters like `temperature` and `max tokens` to fine-tune responses.
- **Langsmith Tracking**: Integrated Langsmith API for project tracking.

## Requirements
- Python 3.x
- Streamlit
- Langchain
- Ollama
- dotenv

## Model Library

Ollama supports a variety of models available at [ollama.com/library](https://ollama.com/library).

Here are some example models that can be downloaded:

| Model                     | Parameters | Size   | Download                      |
|---------------------------|------------|--------|-------------------------------|
| Llama 3.2                 | 3B         | 2.0GB  | `ollama run llama3.2`        |
| Llama 3.2                 | 1B         | 1.3GB  | `ollama run llama3.2:1b`     |
| Llama 3.1                 | 8B         | 4.7GB  | `ollama run llama3.1`        |
| Llama 3.1                 | 70B        | 40GB   | `ollama run llama3.1:70b`    |
| Llama 3.1                 | 405B       | 231GB  | `ollama run llama3.1:405b`   |
| Phi 3 Mini                | 3.8B       | 2.3GB  | `ollama run phi3`            |
| Phi 3 Medium              | 14B        | 7.9GB  | `ollama run phi3:medium`     |
| Gemma 2                   | 2B         | 1.6GB  | `ollama run gemma2:2b`       |
| Gemma 2                   | 9B         | 5.5GB  | `ollama run gemma2`          |
| Gemma 2                   | 27B        | 16GB   | `ollama run gemma2:27b`      |
| Mistral                   | 7B         | 4.1GB  | `ollama run mistral`         |
| Moondream 2               | 1.4B       | 829MB  | `ollama run moondream`       |
| Neural Chat               | 7B         | 4.1GB  | `ollama run neural-chat`      |
| Starling                  | 7B         | 4.1GB  | `ollama run starling-lm`     |
| Code Llama                | 7B         | 3.8GB  | `ollama run codellama`       |
| Llama 2 Uncensored        | 7B         | 3.8GB  | `ollama run llama2-uncensored`|
| LLaVA                     | 7B         | 4.5GB  | `ollama run llava`           |
| Solar                     | 10.7B      | 6.1GB  | `ollama run solar`           |

**Note:** You should have at least 8 GB of RAM available to run the 7B models, 16 GB to run the 13B models, and 32 GB to run the 33B models.
