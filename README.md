
# Automated Resume Screening using Retrieval-Augmented Generation 

This repository contains the full implementation and documentation for the Automated Resume Screening project. The project uses semantic retrieval and large language models (LLMs) to assist hiring teams in screening resumes efficiently and accurately.

---

## 📁 Repository Contents

- `report.pdf` - Final project report written in academic format (ACL/NeurIPS style).
- `code.ipynb` - Google Colab-compatible notebook with full implementation.
- `code demo.pptx` - Presentation slides summarizing the project and demo.
- `README.md` - This file, containing usage instructions and project details.

---

## 🚀 Project Overview

We developed a RAG-style system that:

1. Accepts resumes and job descriptions as input.
2. Embeds resumes using Sentence-BERT.
3. Retrieves top candidates using FAISS based on semantic similarity.
4. Compares skills between candidates and job requirements.
5. Uses the Flan-T5 LLM to generate professional recruiter-style feedback.

---

## 📌 Requirements

To run the notebook, install the following packages:

```bash
pip install sentence-transformers faiss-cpu gradio transformers
```

---

## 🛠️ How to Use

1. Open `code.ipynb` in Google Colab.
2. Upload the resume dataset (CSV format).
3. Enter or paste a job description.
4. Run the notebook cells to view matching resumes, skill gaps, and generated feedback.
5. Download the Excel output for offline use.

---

## 📘 Citation

If you use this project, please cite our report:

```
Automated Resume Screening using Retrieval-Augmented Generation, 
Pavan Kumar Sunkara & Veda Prakash Chiliveru, 2025.
```

---

## 📩 Contact

For questions or collaborations, please reach out via GitHub or email.
