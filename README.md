# AI Empathy Interviewer

Adaptive empathy interviewer powered by the xAI API.

Required environment variable:
- `XAI_API_KEY`

Optional:
- `XAI_MODEL` (defaults to `grok-4.7`)

Render:
- Build command: `pip install -r requirements.txt`
- Start command: `gunicorn app:app`
