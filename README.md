# Medical Report Summarizer

FastAPI + Ollama + Streamlit example that creates doctor- and patient-friendly summaries.

## Quick start (local)

1. Install and run Ollama and pull a model, e.g. `ollama pull gemma3`.
2. Copy `.env.example` to `.env` and adjust `OLLAMA_URL` if needed.
3. Build & run with Docker Compose:
   ```bash
   docker compose up --build
   ```
4. Open Streamlit UI: http://localhost:8501

## Notes
- Do not upload PHI to remote services. This example expects Ollama running locally.
- For production, add authentication, input sanitization, and stronger privacy controls.
