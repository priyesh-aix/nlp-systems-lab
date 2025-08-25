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

## 📂 Folder setup (roughly)  
```bash
nlp-systems-lab/
├─ data/          # datasets (raw + processed)
├─ notebooks/     # Jupyter playgrounds
├─ src/           # actual reusable code
├─ models/        # trained stuff
├─ configs/       # YAML configs, tweakable
├─ docs/          # notes, diagrams, etc.
└─ README.md
```

---

⚠️ Note: this repo isn’t “done.” It will keep mutating. If something looks half-baked… it probably is.  
