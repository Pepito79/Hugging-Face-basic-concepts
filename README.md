# HuggingFace Playground 🐍🤗

Hey there! Welcome to my little **HuggingFace playground** 🚀  

This repo is basically my personal **sandbox** to explore and learn the basics of HuggingFace. It’s not a production project (yet 😅), just a space to play around, experiment, and really understand how things work.

Here’s what I’m messing with here:

- **Tokenizers** – how text gets split into tokens, paired, padded, etc. (`AutoTokenizer`, `tokenize()`, `encode_plus()`, …)  
- **Pre-trained models** – checking out `AutoModel`, `AutoModelForSequenceClassification`, `AutoModelForCausalLM`, and friends  
- **Tensors, padding, truncation** – basically all the stuff to feed text into a model properly  
- **Fine-tuning basics** – trying out small experiments without breaking anything  

---

## 🛠️ What’s inside

- `notebooks/` – interactive notebooks to test stuff and see things in action  
- `examples/` – tiny scripts showing tokenization, text pair encoding, generation…  
- `README.md` – the guide you’re reading right now 😎  

---

## 🚀 Goal

Simple: **get comfortable with HuggingFace**, understand what’s happening behind the scenes, and have fun along the way.  

Whether you’re curious about how tokenizers work, how raw text turns into something a model can understand, or just want to experiment with language models, you’re in the right place!

---

## 💡 Quick Tips

- Python 3 is required  
- Install the basics quickly:
```bash
pip install transformers datasets torch
