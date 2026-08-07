# Hi, I'm Irum Shehryar 👋
NLP Researcher | MSc Information Technology, Metropolia University of Applied Sciences — Graduated May 2026 (GPA 5.00/5.00) | Based in Espoo, Finland

---

## 🌱 Current Focus
Applying for PhD positions in **NLP/AI**, with a research focus on **multilingual NLP, clinical/medical NLP, LLM evaluation, and trustworthy AI** — specifically hallucination detection, grounding, and reliability of LLM-generated text in high-stakes domains.

---

## 🔬 Active Research

### 🩺 SHROOM-Visions 2026 (UncertaiNLP @ EMNLP 2026 shared task)
Solo, independent submission — zero-shot LLM-as-judge hallucination span detection for vision-language model outputs. Ranked **13/28 teams** (Cor+Lbl) among international participants. System uses Claude Haiku 4.5 as primary judge with Claude Sonnet 5 for second-opinion verification on ambiguous error categories, plus rule-based post-processing.
📄 System description paper submitted to OpenReview; arXiv preprint in progress.
🔗 [shroom-visions-hallucination-detection](https://github.com/IrumShehryar/shroom-visions-hallucination-detection)

### 🧠 Medical Grounding Verification (proof-of-concept, in progress)
Extending the SHROOM-Visions hallucination-detection methodology to medical/clinical text, built specifically for PhD research-plan development. Combines direct source-fidelity checking with **retrieval-augmented grounding** (sentence-transformer embeddings + FAISS) against trusted medical references (MedlinePlus), verifying LLM-generated clinical summaries for invented claims, mischaracterizations, and unsupported medical assertions.
🔗 [Medical-grounding-verification](https://github.com/IrumShehryar/Medical-grounding-verification)

### 🇫🇮 Finnish News Topic Classification
Fine-tuned **FinBERT** (TurkuNLP/bert-base-finnish-cased-v1) on labeled Finnish news data, benchmarked against a TF-IDF + Logistic Regression baseline. FinBERT achieved **0.787 macro F1** vs. **0.745** baseline. Includes class-imbalance and data-scarcity error analysis.
🔗 [finnish-news-topic-classification](https://github.com/IrumShehryar/finnish-news-topic-classification)

---

## 🎓 Master's Thesis
**Context-Aware Document-Level Location Selection for Finnish News Articles: A Hybrid Rule-Based and LLM Approach**
Developed in collaboration with **Superhood Oy** — a Finnish neighbourhood-level news platform. Awarded **grade 5/5** — the highest grade at Metropolia University of Applied Sciences.

Built and evaluated a four-configuration NLP pipeline for extracting and ranking geographic locations at postal-code granularity from Finnish news articles, combining:
- **Stanza** for Finnish NER and morphological normalisation
- **Geoapify** for dynamic geocoding and candidate resolution
- **Postal-first hierarchical ranking** for geographic level disambiguation
- **Model Context Protocol (MCP)** with Llama 3.3 70B via Groq for contextual reasoning

**Key result:** 83.33% exact-match accuracy with the full hybrid configuration across 60 Finnish news articles — a 16.66-point improvement over the rule-based baseline.
**Key finding:** Systematic lemmatization failures on Finnish postal-level names point to a data-coverage gap in Finnish NER training corpora, not a tool-architecture limitation.

📄 Published thesis: [URN:NBN:fi:amk-2026051311846](https://urn.fi/URN:NBN:fi:amk-2026051311846)
📊 Evaluation dataset & results: [thesis-nlp-evaluation](https://github.com/IrumShehryar/thesis-nlp-evaluation)

---

## 🛠️ Technical Skills

| Area | Tools & Technologies |
|---|---|
| LLMs & Evaluation | Claude API (Haiku, Sonnet), LLM-as-judge methodology, hallucination/error taxonomy design, prompt engineering, zero-shot evaluation |
| Retrieval & Grounding | RAG pipelines, sentence-transformers, FAISS (vector similarity search), embedding-based retrieval |
| NLP Modeling | FinBERT fine-tuning, transfer learning, Stanza, Finnish NER, lemmatization, TF-IDF, transformer architectures |
| LLM Integration & Agents | MCP (Model Context Protocol), FastMCP, Groq, Llama 3.3 70B |
| ML Foundations | Regression, classification, ablation study design, class-imbalance handling, error analysis |
| Backend | Python, FastAPI, Flask, REST APIs |
| Databases | PostgreSQL, MongoDB, MySQL |
| Data | Pandas, NumPy, evaluation framework design |

---

## 📌 Other Projects

### 🤖 [MCP-practice](https://github.com/IrumShehryar/MCP-practice)
Hands-on exploration of Model Context Protocol — the tool-orchestration framework used in the thesis disambiguation layer.

### 📚 [ML-NLP-Coursework](https://github.com/IrumShehryar/ML-NLP-Coursework)
Notebooks and experiments from NLP and Machine Learning specialisation coursework.

### 🇫🇮 [Finnish-mentor](https://github.com/IrumShehryar/Finnish-mentor)
Prototype language-learning app providing real-time feedback on Finnish grammar and pronunciation.

### 📞 [AsiakasGroupOy](https://github.com/AsiakasGroupOy/Asiakas_Group_Oy)
Backend REST API development for a VoIP application. Implemented CRUD operations and database integration using Flask and MySQL.

---

## 📍 Contact
📧 irum.shehryar@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/irum-shehryar-5334091a3)
🌐 [Portfolio](https://irumshehryar.github.io/portfolio/)
