# Hands-On Fine-Tuning and Evaluating Open LLMs

This repo contains materials from the workshop organized during my time at the Max Planck Institute. The session introduced participants to open-source tools for adapting, evaluating, and interpreting large language models (LLMs) using lightweight infrastructure.

### 🔍 Topics Covered
- Multihead attention and transformer basics
- Fine-tuning GPT-2 using Axolotl and LoRA
- Formatting datasets for supervised and multiple-choice tasks
- Evaluating LLMs with the [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness)
- Model scaling and memory cost estimation
- Positioning on the [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard)

### 📁 Repository Contents

| File                      | Description |
|---------------------------|-------------|
| `Workshop Demo.ipynb`     | Guided notebook covering fine-tuning, generation, and evaluation |
| `lora-8b.yml`             | Example Axolotl config for LoRA-based fine-tuning |
| `generated_data_100.jsonl` | Sample dataset for instruction tuning |
| `mmlu_data.csv`           | Multiple-choice dataset for evaluation |
| `fit_full_mmlu_pro_2pl.R` | R script for 2PL IRT modeling of LLM outputs |
| `llm-psychometrics-workshop.pdf` | Slide deck from the workshop |
| `README.md`               | This file |

### 🔗 References
- [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) – Lightweight LLM fine-tuning
- [lm-eval-harness](https://github.com/EleutherAI/lm-evaluation-harness) – Benchmarking framework
- [System Memory Calculator](https://llm-system-requirements.streamlit.app/) – Estimate model resource needs
- [GPT-2 on Hugging Face](https://huggingface.co/openai-community/gpt2)

---

This material was created for educational use and open-source LLM experimentation. For questions or collaborations, feel free to reach out!
