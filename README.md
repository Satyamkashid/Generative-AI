# GenAI Learnings

This project demonstrates Generative AI workflows using [LangChain](https://github.com/langchain-ai/langchain), [Streamlit](https://streamlit.io/), and integrations with OpenAI, Anthropic, HuggingFace, and Google GenAI APIs.

## Project Structure

```
GenAI_Learnings/
│
├── .env.example         # Example environment variables
├── requirements.txt     # Python dependencies
├── generate_requirements.py  # Script to auto-generate requirements.txt
├── <your Python scripts and modules>
└── ...
```

## Setup

1. **Clone the repository**

   ```sh
   git clone <your-repo-url>
   cd GenAI_Learnings
   ```

2. **Install dependencies**

   ```sh
   pip install -r requirements.txt
   ```

3. **Configure environment variables**

   - Copy `.env.example` to `.env`:
     ```sh
     cp .env.example .env
     ```
   - Fill in your API keys and secrets in `.env`.

## Usage

- Run your main Streamlit app or other scripts as needed. For example:
  ```sh
  streamlit run <your_main_app.py>
  ```

## Environment Variables

The following environment variables are required (see `.env.example`):

- `OPENAI_API_KEY`
- `ANTHROPIC_API_KEY`
- `HUGGINGFACE_API_KEY`
- `GOOGLE_GENAI_API_KEY`
- `STREAMLIT_SECRET_KEY`

## Scripts

- `generate_requirements.py`: Scans all Python files and generates a `requirements.txt` based on imports.

## Dependencies

Major libraries used:
- `langchain`, `langchain_*` (for LLM orchestration)
- `streamlit` (for UI)
- `numpy`, `sklearn`, `pydantic` (for data and validation)
- `dotenv` (for environment variable management)

See `requirements.txt` for the full list.