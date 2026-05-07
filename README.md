# Judge-Eval Pipeline: LLM-as-a-Judge for Cultural Intelligence

This repository provides an automated framework for evaluating LLM outputs using **Gemma 2** as a standardized "Judge." It specifically focuses on identifying linguistic drift and cultural misalignment in non-Western contexts.

## 🚀 Why This Matters
Standard benchmarks often fail to capture the nuances of emerging markets. This pipeline allows developers to create custom, domain-specific rubrics to ensure their AI is safe and effective for local deployment.

## 💡 Features
* **Automated Scoring:** Uses p-agent to orchestrate evaluation loops.
* **Local-First:** Runs entirely via Ollama, protecting sensitive evaluation datasets[cite: 1].
* **Cultural Intelligence:** Pre-configured rubrics for African linguistic nuances and idiomatic accuracy[cite: 1].

## 🛠️ Tech Stack
* **Orchestrator:** p-agent[cite: 1]
* **Judge Model:** Google Gemma 2[cite: 1]
* **Environment:** Python 3.10+[cite: 1]

## 📈 Use Cases
* **A/B Testing:** Compare two models on their ability to handle Nigerian Pidgin or Yoruba idioms[cite: 1].
* **Safety Auditing:** Detect bias in model responses before they reach production[cite: 1].

---
*A project by Temitope Ajao | Ex Machina Technologies*
