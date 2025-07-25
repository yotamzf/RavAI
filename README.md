# 🤖 RavAI — Rabbinic Language Model Training Pipeline

A modular, Colab‑ready pipeline for fine‑tuning open‑source Hebrew LLMs (e.g., LLaMA‑2‑Hebrew, Dicta‑Maivin) on rabbinic texts such as Rashi, Talmud, Mishnah, and Tanakh. The model learns to generate intelligible Hebrew answers in the style of your selected rabbi — complete with accurate citations and creative חידושים.

---

## 🚀 Quick Start (Colab)

Set these variables at the top of your Colab notebook:

```bash
%env GIT_REMOTE=https://github.com/USERNAME/rabbinic-llm.git
%env GH_TOKEN=ghp_xxx                     # GitHub token with repo write access  
%env DATA_JSONL=/content/Rashi.jsonl     # Upload or path to your corpus file  
%env RABBI_NAME_EN=RASHI                 # Unique English name (e.g., RASHI, RAMBAM)
