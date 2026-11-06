# Prompt Engineering & AI Productivity Toolkit

A beginner-friendly, hands-on project covering prompt engineering, structured outputs, AI-assisted coding/debugging, prompt evaluation, and reusable productivity workflows.

## Learning objectives
1. Practice zero-shot and few-shot prompting.
2. Use roles, context, instructions, examples, and constraints.
3. Request and validate structured JSON outputs.
4. Build prompts for summarization, classification, and generation.
5. Use an AI assistant for coding and debugging with verification.
6. Evaluate prompts using reusable test cases and a simple report.
7. Build reusable workflows for summarization, email, resume, coding, and research assistance.

## Repository structure

```text
prompt-engineering-ai-productivity/
├── README.md
├── requirements.txt
├── Prompt_Engineering_AI_Productivity.ipynb
├── templates/
│   └── prompt_templates.json
└── reports/
    └── prompt_evaluation_report.csv
```

## Run in Google Colab
1. Upload `Prompt_Engineering_AI_Productivity.ipynb` to Google Drive, or open it from GitHub in Google Colab.
2. Run the cells from top to bottom.
3. The notebook uses sample data and does not require an API key.
4. Optional LLM integration can be added later by connecting a model provider and storing its API key in Colab Secrets. Never hard-code API keys.

## Publish to GitHub
1. Create a new GitHub repository named `prompt-engineering-ai-productivity`.
2. Upload the files in this folder, preserving the directory structure.
3. Add the Colab notebook link to the repository description or README.

## Important
The included evaluation is a lightweight educational framework. It checks output structure and expected content; it is not a substitute for human review, factual verification, privacy review, or safety testing.
