# GoodFoods AI Reservation Agent (Challenge)
Demo + starter implementation of a multi-location reservation assistant.

## Quickstart
1. python -m venv venv && source venv/bin/activate
2. pip install -r requirements.txt
3. python db_seed.py
4. streamlit run app/streamlit_app.py

## Files
- db_seed.py — generate 75 restaurants and create DB
- app/streamlit_app.py — demo UI
- app/llm_client.py — LLM wrapper & tool-runner (put your LLM API call)
- app/tools.py — deterministic tools (search/create/cancel)
