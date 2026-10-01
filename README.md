# OpenAI API Call

A simple Python project demonstrating how to make an API call to OpenAI and generate an AI response.

## Technologies

* Python
* OpenAI Python SDK
* python-dotenv
* OpenAI API

## Setup

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
.\venv\Scripts\Activate.ps1
```

Install the required packages:

```bash
pip install openai python-dotenv
```

Create a `.env` file:

```env
OPENAI_API_KEY=your_api_key_here
```

## Run

```bash
python app.py
```

## Example

The program sends a prompt to an OpenAI model and displays the generated response in the terminal.

## Security

Never upload your actual `.env` file or API key to GitHub.

