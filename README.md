## gemma-3n-e2b-finance
## What
This notebook fine-tunes the Unsloth Gemma 3N E2B model using LoRA adapters on merged finance instruction datasets, runs a sample inference, and shows how to push adapters and a merged model to the Hugging Face Hub.

## Quick start
1. Open `gemma_3n_e2b_finance.ipynb` in Jupyter/Colab or VS Code and run cells top-to-bottom.
2. Install the notebook's dependencies. Key packages: `unsloth`, `transformers`, `peft`, `trl`, `datasets`, `huggingface_hub`, `bitsandbytes`.

## Notes
- The notebook configures a 4-bit model with LoRA adapters for efficient fine-tuning.
- It merges two finance instruction datasets, formats prompts for Gemma chat-style input, and trains with `SFTTrainer`.
- Final steps save/push LoRA adapters and demonstrate merging adapters into the base model before pushing the merged model to the Hub.

## Minimal checklist
- Open notebook
- Install dependencies
- Run training cells -GPU recommended-
- Save and push adapters/model to Hugging Face

## Model adapters on [Hugging Face](https://huggingface.co/huseyincavus/gemma-3n-e2b-finance-lora)
