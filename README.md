# AI_Decision-copilot
This is a small starter app for an AI decision copilot. It lets you:

- upload messy CSV data
- profile the data quality
- answer clarifying questions
- run what-if scenario adjustments
- get a recommended option with explanation and risk notes

## Run locally

```bash
python app.py
```

Open `http://127.0.0.1:8000` in your browser.

## Expected data shape

Use a CSV with a header row. Each row should represent one candidate option, customer segment, supplier, campaign, or decision scenario.

## What this starter does

- infers numeric vs categorical columns
- suggests clarifying questions automatically
- lets you choose the main metric and whether to maximize or minimize it
- optionally uses a second metric as a risk penalty
- applies percentage changes to numeric columns as what-if scenarios

## Good next steps

- add login and saved analysis history
- connect a real LLM for conversational follow-up questions
- support Excel uploads and charts
- train domain-specific decision scoring rules
