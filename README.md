# Leaf Video Analysis

Motion quantification for leaf movement videos.

## Structure

- `motion-quant-back/` — Flask backend (Python)
- `motion-quant-front/` — Angular frontend

## Run locally

**Backend:**
```bash
cd motion-quant-back
python -m venv .venv
.venv/Scripts/pip install -r requirements.txt
.venv/Scripts/python app.py
```
Runs at `http://localhost:5000`.

**Frontend:**
```bash
cd motion-quant-front
npm install
npm start
```
Runs at `http://localhost:4200`.
