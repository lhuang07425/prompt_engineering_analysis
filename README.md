# Prompt Code Generation Analysis

This notebook analyzes how different prompting techniques affect AI code generation quality, using CodeBLEU scores for Anthropic Claude Sonnet 4.5 and OpenAI ChatGPT 5.0. :contentReference[oaicite:0]{index=0}  

## Contents

- `prompt_analysis.ipynb`  
  - Loads the `code_gen_data.csv` dataset  
  - Computes summary statistics and paired t tests  
  - Generates plots comparing prompting methods and models  

## Data

- `code_gen_data.csv` (task id, language, prompting method, model, CodeBLEU score)  
- Original data and notebook are hosted in the linked GitHub repository

## Requirements

- Python 3  
- Jupyter Notebook or JupyterLab  
- `pandas`, `numpy`, `scipy`, `matplotlib`

## How to use

1. Install the dependencies.  
2. Place `code_gen_data.csv` in the same directory as `prompt_analysis.ipynb`.  
3. Open the notebook and run all cells to reproduce the figures and statistics reported in the project.
