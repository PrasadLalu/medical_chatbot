# Medical Chatbot

1. **Install `uv`:**
   ```bash
   pip install uv

   uv --version
2. **Create a Virtual Environmen:**
    ```bash
    uv venv .venv --python=3.12
3. **Active Virtual Environment:**
    ```bash
    .venv\Scripts\activate
4. **Initialize the `uv` Project:**
    ```bash
    uv init
5. **Add Dependencies (e.g. add `python-dotenv`):**
    ```bash
    uv add python-dotenv

### Run:
```
uv run streamlit run main.py --server.runOnSave true
```