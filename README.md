# 🧠 Research Agent (n8n + LLMs)

An AI-powered research assistant pipeline built with [n8n](https://n8n.io), Large Language Models, and human-in-the-loop feedback. It accepts a research topic and description via a public webhook and generates structured academic content in LaTeX format.

## ✨ Features

- 📩 Public webhook to submit topic + description
- 🧾 Auto-generates:
  - Abstract
  - Introduction
  - Literature Review (with LaTeX table)
  - Methodology (guided by prior work + human input)
  - References (IEEE-style, LaTeX `\bibitem`)
- 📄 Outputs a complete `.tex` file (IEEE format)
- 📤 Optional export to Overleaf or GitHub
