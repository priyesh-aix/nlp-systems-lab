# 🧠 NLP Systems Lab  

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)

So here’s the deal: **`nlp-systems-lab`** is where I mess around with NLP, but in a way that *could* (with a bit of polish) run in production. It’s not a “101 tutorials” dump. It’s more like: I try an idea → I clean it up → I stash it here with configs, docs, and some tests so future-me (or you) can use it without swearing at the code.  

---

## 🎯 What’s the point?  
- Go through the whole ladder: tokenize → embed → transformer models.  
- Keep things “prod-ready” (configs, logging, reproducibility).  
- Be honest about trade-offs. Sometimes simpler works better — I’ll flag those.  
- Write reusable code instead of endless notebooks full of half-working junk.  
- Final project: build a banking chatbot-ish assistant. (Why banking? Because that’s the domain I know, and it forces you to think about compliance, edge cases, etc.)  

---

## 🏭 Why not just use HuggingFace and call it a day?  
You could, sure. But this repo’s about **learning by building**. So yeah, some things are reinvented here on purpose. Plus, I want to show how you’d structure this stuff if it had to pass code review at a bank or startup.  

Some highlights:  
- Typed Python, PEP8 (well… mostly), docstrings.  
- Config files instead of random constants.  
- Model versioning & monitoring hooks.  
- Lots of diagrams / tables because I learn better that way.  
- “Mini builds” → each section leaves behind something runnable.  

---

## 📋 Requirements
- **Python** 3.10+
- **pip** (comes with Python)
- (Optional) **virtualenv** or **conda** for environment management
- **Git** (to clone the repository)
- **JupyterLab** (installed via pip below)

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/priyesh-aix/nlp-systems-lab.git
cd nlp-systems-lab
```

### 2. Create & activate virtual environment
```bash
python -m venv .venv
# macOS/Linux
source .venv/bin/activate
# Windows PowerShell
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Install & launch JupyterLab
```bash
pip install jupyterlab
jupyter lab
```

### 5. Run the notebooks
Open any notebook from:
```
notebooks/nlp/
```

---

## 📂 Directory Layout  
```bash
.
├── nlp-systems-lab
│   ├── data
│   │   ├── hotel-reviews.csv
│   │   ├── sample.txt
│   │   └── tweets.csv
│   ├── notebooks
│   │   └── nlp
│   │       ├── text_processor.ipynb
│   │       └── text_processor_pd.ipynb
│   ├── notes
│   │   ├── 1_intro
│   │   │   └── ml_intro.ipynb
│   │   └── 2_nlp
│   │       └── nlp_notes.ipynb
│   ├── README.md
│   └── requirements.txt
---
```

## 📚 Recommended Resources

A curated, chronological list of books and study material for learning Machine Learning, Deep Learning, and NLP.  
Where possible, open-access PDFs are linked directly. Otherwise, references to standard texts are included.

---

### 1️⃣ Foundations (Math + ML Basics)
- **Mathematics for Machine Learning** — Marc Peter Deisenroth, A. Aldo Faisal, Cheng Soon Ong  
  🔗 [Book site](https://mml-book.github.io/) | [Direct PDF](https://mml-book.github.io/book/mml-book.pdf)

- **Dive into Deep Learning (D2L)** — Aston Zhang, Zachary Lipton, Mu Li, Alex Smola  
  🔗 [Book site](https://d2l.ai) | [Direct PDF](https://d2l.ai/d2l-en.pdf)  
  📖 Hands-on introduction with interactive Jupyter notebooks.

---

### 2️⃣ Core Machine Learning
- **Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow** — Aurélien Géron  
  📕 Practical, implementation-first (not open access).

- **Understanding Deep Learning** — Simon J.D. Prince  
  🔗 [Book site](https://udlbook.github.io/udlbook/) | [Direct PDF](https://udlbook.github.io/udlbook/udlbook.pdf)  
  📖 Accessible but mathematically rigorous guide to deep learning.

---

### 3️⃣ Probabilistic & Theoretical ML
- **Pattern Recognition and Machine Learning (PRML)** — Christopher M. Bishop  
  📖 Classic ML theory and probabilistic foundations (2006).  
  🔗 [Official PDF (Microsoft Research)](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)

- **Probabilistic Machine Learning (Vol. 1: Introduction, Vol. 2: Advanced Topics)** — Kevin P. Murphy  
  📖 Comprehensive modern treatment of probabilistic ML.  
  🔗 [Publisher page](https://probml.github.io/pml-book/) (not openly available as PDF).

---

### 4️⃣ Natural Language Processing (NLP)
- **Speech and Language Processing (3rd Edition Draft)** — Daniel Jurafsky & James H. Martin  
  🔗 [Book site](https://web.stanford.edu/~jurafsky/slp3/) | [Direct PDF](https://web.stanford.edu/~jurafsky/slp3/slp3.pdf)

- **Natural Language Processing with Python (NLTK Book)** — Steven Bird, Ewan Klein, Edward Loper  
  🔗 [Book site](https://www.nltk.org/book/)  
  📖 Code-oriented introduction to NLP using Python.

---

### 5️⃣ Advanced & Specialized Topics
- **Deep Learning** — Ian Goodfellow, Yoshua Bengio, Aaron Courville  
  🔗 [Official site](https://www.deeplearningbook.org/) (PDF no longer openly distributed).

- **Graph Representation Learning** — William Hamilton  
  🔗 [Book site](https://www.cs.mcgill.ca/~wlh/grl_book/) | [Direct PDF](https://www.cs.mcgill.ca/~wlh/grl_book/files/GRL_Book.pdf)

---

⚠️ Note: this repo isn’t “done.” It will keep mutating. If something looks half-baked… it probably is.  
