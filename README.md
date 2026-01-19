# Running the project locally (without Docker)

```bash
python3 -m venv venv
source venv/Scripts/activate

pip install -r requirements.txt

uvicorn app.main:app --reload
```

# Ports

- App `localhost:8000`
- Metrics `localhost:8000/metrics`
- Prometheus `localhost:9090`
- Grafana: `localhost:3000`
