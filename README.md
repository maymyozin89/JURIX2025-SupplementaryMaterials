# Supplementary Materials  
## *From Court Decisions to Guiding Principles: Advancing Complex Legal Summarization with LLMs*  
**JURIX 2025**

This repository contains the supplementary materials for our paper presented at **JURIX 2025**:  
> **From Court Decisions to Guiding Principles: Advancing Complex Legal Summarization with LLMs**

It includes detailed prompt designs, sample court decisions and generated *Leitsätze*, model outputs across prompting strategies, and evaluation protocols used in our experiments.

---

## 📄 Contents

- `appendix.md` – Full appendix describing all prompting strategies, prompt examples, evaluation setup, and references.
- `prompts/` – Prompt templates used in:
  - SimplePrompt
  - Expert-StructuredPrompt
  - ChatCoI (collaborative chain-of-instructions)
  - SelfCoI (self-generated instructions)
- `sample_cases/` – Selected court decisions and corresponding gold-standard *Leitsätze*.
- `outputs/` – Generated *Leitsätze* from various prompting strategies.
- `evaluation/` – Evaluation outputs, including GPT-based and human assessments.
- `figures/` – Visualizations or charts referenced in the paper (if applicable).

---

## 📌 How to Use

This repository is designed to support transparency and reproducibility. Researchers can:

- Explore prompt variants and their linguistic or structural effects.
- Compare LLM outputs under different prompting strategies.
- Review human and automated evaluation criteria and outcomes.

All examples are anonymized or adapted where necessary to protect personal/legal information.

---

## 📚 Citation

If you use or reference this work, please cite the following paper:

```bibtex
@inproceedings{yourcitation2025,
  title     = {From Court Decisions to Guiding Principles: Advancing Complex Legal Summarization with LLMs},
  author    = {Your Name and Coauthor Name},
  booktitle = {Proceedings of the 2025 JURIX Conference on Legal Knowledge and Information Systems},
  year      = {2025}
}
