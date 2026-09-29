# DeepSeek-R1 with LangChain and Hugging Face

This project demonstrates how to use the **DeepSeek-R1** language model with **LangChain** and **Hugging Face**.

## Model

* **Model:** DeepSeek-R1
* **Provider:** DeepSeek AI
* **Platform:** Hugging Face
* **Framework:** LangChain
* **Interface:** `ChatHuggingFace` + `HuggingFaceEndpoint`

## Project Structure

```text
deepseek-r1/
│
├── chatbot.py
├── requirements.txt
└── README.md
```

## Installation

Create and activate a virtual environment, then install the required packages:

```bash
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file in the project directory and add your Hugging Face API token:

```text
HUGGINGFACEHUB_API_TOKEN=your_huggingface_token
```

**Do not upload the `.env` file or your API token to GitHub.**

## How to Run

Run the Python file:

```bash
python chatbot.py
```

The program sends a question to the DeepSeek-R1 model and prints the generated response in the terminal.

## Example

Input:

```text
Who is man in ancient time?
```

The model generates an AI response based on the question.

## Technologies Used

* Python
* LangChain
* Hugging Face
* DeepSeek-R1
* python-dotenv

## Learning Objective

The purpose of this project is to understand how to:

1. Connect LangChain with Hugging Face.
2. Use a hosted LLM through `HuggingFaceEndpoint`.
3. Use `ChatHuggingFace` for chat-based interaction.
4. Send prompts to DeepSeek-R1.
5. Generate and display AI responses.

## Author

**Sachin Sagar**
