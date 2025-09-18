# Industrial-Technology-Research-Institute-work-example Generative AI Internship Project (Dec 2024 – Apr 2025)

This repository documents my work during my internship at the **Industrial Technology Research Institute (ITRI), Taiwan**, as part of the **Generative AI Large Language Model Project**.
Due to a **Non-Disclosure Agreement (NDA)**, I am unable to share the project source code. Instead, this repository serves as a record of my contributions and includes presentation slides that summarize my work.

---

## 📌 Project Highlights

### 1. Traditional Chinese Table VQA Dataset

* Scraped **25,000+ Wikipedia pages** for raw data.
* Extracted, cleaned, and parsed **table contents into JSON**.
* Rendered structured tables into **table images** using an automated tool.
* Generated **10,000+ Question-Answer pairs** via the GPT-4 API to support Visual Question Answering (VQA) tasks.

### 2. Novel Evaluation Metric

* Independently designed the **"Redundancy Penalty Accuracy"** metric.
* Addressed the absence of a standardized evaluation method for **table recognition and reconstruction tasks**.

### 3. Model Fine-Tuning & Performance

* Fine-tuned **Qwen2.5-VL** using targeted synthetic data generated via GPT-4.
* Achieved a **17% improvement in accuracy** (from **75% → 92%**) on table recognition benchmarks.

---

## 📊 Presentation

As the project code is under NDA, the following **PowerPoint slides** are provided to illustrate the work process, dataset pipeline, evaluation methodology, and experimental results:

➡️ [View the Presentation Slides](./Construction of a Traditional Chinese Table Image and QA Dataset.pptx)
➡️ [View the Presentation (PDF)](./Construction of a Traditional Chinese Table Image and QA Dataset.pdf)
---

## 🛠️ Tech Stack

* **Programming Languages:** Python
* **Models & APIs:** Qwen2.5-VL, GPT-4 API
* **Techniques:** Data scraping, JSON parsing, computer vision preprocessing, dataset generation, fine-tuning
* **Domain:** Table VQA, Table Recognition & Reconstruction, Evaluation Metrics



要不要我幫你再加一段 **"Future Work"** 或 **"Lessons Learned"** section？ 這樣可以讓你的 GitHub README 看起來更完整、更像研究成果展示。
