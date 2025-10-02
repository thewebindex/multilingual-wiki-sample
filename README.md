# Multilingual Wiki Dataset Sample (5 Languages)

This dataset contains a sample of **500 structured wiki entries** across 5 languages,  
sourced from [web.wiki](https://web.wiki). It mirrors the full multilingual dataset  
architecture used for AI, NLP, and research.

## 📂 What's included
- `Dataset_Sample.csv` : Sample rows with multilingual entries  
- `languages.txt` : ISO codes of included languages  
- `README.txt` : License and usage details  

## 🌍 Mirrors
- [Kaggle Dataset](https://kaggle.com/datasets/thewebindex/multilingual-wiki-dataset-sample-5-languages)  
- [Hugging Face Dataset](https://huggingface.co/datasets/thewebindex/multilingual-wiki-sample)  
- [Full Datasets on Gumroad](https://thewebindex.gumroad.com/)  

## ⚖️ License
This free sample dataset is provided by **web.wiki** for evaluation, research,  
and educational purposes only.  

- Redistribution, resale, or repackaging of this dataset, in whole or in part,  
  is not permitted without prior written consent.  
- Full datasets are available via [The Web Index on Gumroad](https://thewebindex.gumroad.com/).  

## 📝 Citation
If you use this dataset, please credit:  
**The Web Index (web.wiki)** – Multilingual Wiki Dataset Sample  

## 🚀 Quick Usage
You can load this dataset directly with 🤗 Datasets:

```python
from datasets import load_dataset

dataset = load_dataset("thewebindex/multilingual-wiki-sample")
print(dataset)
