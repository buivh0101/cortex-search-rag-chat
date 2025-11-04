# Cortex Search RAG Chat

Chat over your documents with Snowflake Cortex Search and Streamlit.

## Files

- `chat_with_unstructured_data_app.py` — Streamlit chat app that retrieves context from a Cortex Search service and streams a model response. :contentReference[oaicite:0]{index=0}
- `BUILD_RAG_WITH_CORTEX_SEARCH.ipynb` — Notebook that builds a RAG flow with Cortex Search.

## How it works

1. The app reads your chat messages.
2. It queries a Cortex Search service and returns text chunks.
3. It adds those chunks to the system message.
4. It calls the model and streams the answer to the UI. :contentReference[oaicite:1]{index=1}

