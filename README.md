#  Fine-Tuning Gemma 2B on Dolly Dataset

This project demonstrates how to fine-tune the **Gemma 2B** open-weight LLM from Google using the **Dolly-15k** dataset in a Colab environment. It includes minimal configuration using `KerasNLP` and Hugging Face, supports LoRA-based parameter-efficient fine-tuning, and targets instructional-style dialogue generation.

---

##  Features

-  Loads and tokenizes the Dolly dataset (1k samples)
-  Converts dataset to prompt-response format
-  Fine-tunes Gemma 2B using KerasNLP
-  LoRA support (Low-Rank Adaptation)
-  Google Colab-compatible

---

##  File Structure

- `Fine_Tune.ipynb`: Main notebook with full training and generation pipeline

---

##  Requirements

- `keras`
- `keras-nlp`
- `transformers`
- `datasets`
- `huggingface_hub`

Install with:

```bash
pip install keras keras-nlp datasets transformers
```
## How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/MayankSethi27/Fine-Tunning-Gemma.git
   cd Fine-Tunning-Gemma
   ```

Open Fine_Tune.ipynb in Google Colab

Run all cells to:

1.Load Dolly dataset
2.Tokenize prompts
3.Fine-tune with LoRA
4.Generate responses

## Dataset
Dolly 15k — a high-quality human-generated instruction-following dataset from Hugging Face.

## Model
Gemma 2B
Trained via KerasNLP with optional LoRA integration.
