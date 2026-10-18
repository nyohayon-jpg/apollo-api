# apollo-api

FastAPI backend for **Project Apollo**, built by Bluebird Labs for Greenleaf Grocers.

## Team
- Joe Smith – project lead
- Maya Cohen – backend
- Daniel Levi – frontend
- Priya Shah – data / imports
- Client contact: Sarah Kim (Greenleaf Grocers)

## Endpoints (planned)
- `GET /products` – product catalog per store
- `GET /sales?range=7d|30d` – sales summaries
- `GET /alerts/stock` – low-stock alerts

## Run locally
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```
