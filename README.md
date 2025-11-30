# Influence and Comms Tool

A small, opinionated set of prompts and resources to help product people write clearer, more effective communication (for execs, cross-functional teams, customers) using LLMs like Claude.

This is a **workflow + structure** demo, not an app. It’s meant to show how I think about AI-assisted product work.

---

## Why this exists (for AI product leaders)

This project is designed to demonstrate:

- **Problem-first thinking**  
  High-stakes product comms are slow and inconsistent. This treats comms as a repeatable process, not a one-off talent.

- **Thoughtful use of LLMs**  
  Uses a structured system prompt + reusable resources (personas, frameworks, checklist) instead of a single “clever prompt”.

- **Workflow design**  
  Focuses on how a PM actually works: from rough notes → tailored draft → quality pass, with clear roles for the human vs. the model.

- **Quality and evaluation**  
  Examples + a simple checklist make “what good looks like” explicit and reviewable.

---

## How to use

1. **Load the core prompt**
   - Copy `prompt.md` into the system / main prompt area in Claude (or another LLM).

2. **Describe the task**
   - Goal (e.g. get exec buy-in, align a squad, inform customers)  
   - Audience (e.g., senior executives, engineers, marketing, legal)  
   - Channel (email, Slack, doc, deck)  
   - Constraints (tone, length, must-include points)  
   - Any raw notes or draft text

3. **Optionally pick a framework**
   - Ask the model to use the knowledge from `resources/` to pick a framework
---

## Repo structure

```text
influence-and-comms-tool/
├─ prompt.md                  # Core system prompt for the LLM
├─ README.md                  # Project overview (this file)
└─ resources/
   ├─ how-to-win-friends-and-influence-people.pdf          # by Dale Carnegie
   ├─ Jane Austen_ Persuasion.docx             # by Jane Austen
   ├─ prat_communication.pdf             # Common communication framework
   ├─ The Project Gutenberg eBook of Public Speaking.docx           # Open sourced public speaking book
   └─ The Project Gutenberg eBook, The Knack of Managing, by Lewis K.docx    # Open sourced management book
