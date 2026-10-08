
# Empathy Interviewer

A small Flask site that uses an OpenAI model as an adaptive empathy interviewer.

## Why this version is different
It does **not** begin by asking for a problem or goal. It starts by understanding the person and follows what they choose to share. It only introduces AI after a meaningful goal, challenge, curiosity, aspiration, or process emerges naturally.

## Run locally

1. Install dependencies:
   `pip install flask openai`

2. Set your OpenAI API key:
   - macOS/Linux: `export OPENAI_API_KEY="..."`
   - PowerShell: `$env:OPENAI_API_KEY="..."`

3. Start the server:
   `python app.py`

4. Open:
   `http://127.0.0.1:5000`

## Privacy
Conversation text is sent to the OpenAI API when running this app. Do not use sensitive information unless your deployment and account settings are appropriate for it.
