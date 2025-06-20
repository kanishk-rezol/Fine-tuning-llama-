# 🦙 Fine-Tuning LLaMA 3 on Resume HTML Data with Unsloth

Fine-tuned the LLaMA 3 model using Unsloth on structured resume HTML templates. The model is trained to convert plain resume content into clean, ATS-optimized HTML resumes using Tailwind CSS and semantic formatting.

---

## 📌 Objective

Build an instruction-tuned LLaMA model that:
- Accepts plain text resume content and a job category.
- Outputs a responsive HTML resume using Tailwind CSS.
- Supports various domains like Data Analyst, Developer, and Marketing.

---

## 📂 Dataset Format

Custom dataset in CSV with the following columns:

- `Resume_str` → Plain text resume content  
- `Resume_html` → Target structured HTML resume  
- `Category` → Job role like Data Scientist, Software Engineer, etc.

Each row is converted into an instruction format like:


![Demo](Screenshot.png)

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/kanishk-rezol/Fine-tuning-llama-
```