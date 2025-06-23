# gpt2-finetuning-openwebtext
Fine-tuning GPT-2 using a small OpenWebText subset with HuggingFace

# GPT-2 Fine-Tuning on OpenWebText (Small Subset)

This project fine-tunes the GPT-2 language model using a small sample from the OpenWebText dataset via HuggingFace Transformers.

⚠️ Notebook may show as “Invalid Notebook” on GitHub
Due to a known GitHub rendering issue with some Jupyter notebooks using widgets or Colab outputs, the preview of FineTuning_GPT2.ipynb may not display correctly in the browser.
However The notebook is fully functional and runs without issues in Google Colab, Jupyter Notebook, or VS Code. You can download it and run locally without modification

##  Project Highlights
- Fine-tuned GPT-2 on ~200 samples using Google Colab
- Improved perplexity from 32.5 → 18.4
- Text generation improved in fluency and topic relevance
- Done using HuggingFace's Trainer API

##  Tech Stack
- Python
- HuggingFace Transformers
- Datasets Library
- PyTorch
- Google Colab (Free tier GPU)

##  Files
- `FineTuning_GPT2.ipynb`: Full training, evaluation, and inference workflow

##  Note
This is a **proof-of-concept project** under resource constraints. Only 1% of OpenWebText was loaded, with 200 samples used for training.

##  Results
- **Perplexity (base GPT-2)**: ~32.5
- **Perplexity (fine-tuned GPT-2)**: ~18.4
- **Qualitative improvement**: More coherent and topic-aligned generations

