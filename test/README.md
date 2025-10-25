# RAG-Anything Test Files

## Setup

Before running the test, make sure to set your OpenAI API key as an environment variable:

```bash
export OPENAI_API_KEY="your-api-key-here"
```

## Files

- `e2e.py` - End-to-end test script for RAGAnything framework
- This script demonstrates secure API key handling using environment variables

## Running the Test

```bash
python e2e.py
```

## Security

This implementation uses environment variables for API keys instead of hardcoding them, following security best practices.