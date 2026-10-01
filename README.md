# Autonomous AI Customer Lead Triage Pipeline 🚀

An enterprise-grade data automation pipeline built to intercept incoming customer inquiries, analyze user sentiment, extract structured labels via JSON formatting, and dynamically route responses on autopilot.

## 🛠️ Architecture & Tech Stack
* **Workflow Automation Engine:** Make.com
* **Large Language Model (LLM):** Google Gemini Pro API
* **Database / Data Warehouse:** Google Sheets API
* **Data Engineering Blocks:** Native JSON Parsers, Conditional Logic Filters

## 🧠 Structural Core
1. **Trigger:** Monitors data intakes for newly added customer queries.
2. **Classification:** Prompts an LLM to generate responses contained within target structural frameworks (`{"answer": "string", "urgency": "HIGH/LOW"}`).
3. **Data Parsing:** A processing block catches the string output, cracks open the object keys, and routes isolated dynamic tokens.
4. **Data Syncing:** Updates structural databases, sorting elements cleanly into separate text and classification value tracks.

## 📁 How to Use This Blueprint
1. Download the `blueprint.json` file from this repository.
2. Open your Make.com dashboard and create a blank scenario.
3. Click the three dots `...` on the bottom toolbar, select **Import Blueprint**, and upload this file to immediately deploy the visual pipeline map!
