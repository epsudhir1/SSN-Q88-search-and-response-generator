# Learning From Events – Custom GPT Pack

This repository provides a ready-to-use **Custom GPT instruction set** and templates to help generate a quarterly/periodic **Learning From Events** report from incidents, near misses, and unsafe act/condition reports.

## Included files

- `gpt/instructions.md`: Full system instruction for your Custom GPT.
- `gpt/prompt_starters.md`: Suggested prompt starters for users.
- `templates/data_dictionary.md`: Required and optional fields for uploaded data.
- `templates/report_template.md`: Report output structure and formatting guide.

## How to use

1. Open ChatGPT and create a new Custom GPT.
2. Copy the contents of `gpt/instructions.md` into the GPT **Instructions** field.
3. Add relevant files (CSV/XLSX/PDF exports) when running the GPT.
4. Use a prompt starter from `gpt/prompt_starters.md`.
5. Review output for outliers and factual errors before circulation.

## Date/period defaults

- For this manager request, set period as:
  - **Start:** `2026-01-01`
  - **End:** `2026-03-31`
- Deadline context from manager note:
  - **Completion target:** `2026-04-08`
