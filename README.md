# flask_v1 — Flask learning iteration (v1)

Small Flask practice project while learning:
- routing
- HTML templates (Jinja-ready)
- basic app structure

This repo represents an early iteration of my Flask learning progression.
See `flask_v2` and `flask_v3` for later iterations.

## What's included

- **Simple route** (`/`) — Returns plain text response
- **Template route** (`/hello`) — Renders HTML template (static HTML, no Jinja features yet)
- Basic Flask app structure with templates folder

> **Note:** Jinja is Flask's templating engine that allows dynamic content in HTML using `{{ variables }}` and `{% logic %}`. This project uses `render_template()` but doesn't yet use Jinja syntax.

## Quick start

```bash
pip install -r requirements.txt
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

## Routes

- `/` — Hello World (plain text)
- `/hello` — Hello page (HTML template)
