#  Model Evaluation using TOPSIS

## Overview
This project evaluates different chatbot models using the **TOPSIS** ranking method based on three key factors:  
1. **Average Similarity Score** - Measures how similar chatbot responses are.  
2. **Inference Speed** - Simulated processing speed of the model.  
3. **Model Size** - Simulated storage size of the model.  

## Models Used
The following pre-trained models were evaluated:  

| Model Name                           | Type                     |
|--------------------------------------|--------------------------|
| `EleutherAI/gpt-neo-125M`            | Small GPT-Neo            |
| `microsoft/DialoGPT-medium`         | Medium DialoGPT          |
| `facebook/blenderbot-400M-distill`  | Distilled BlenderBot     |

## Installation & Dependencies
Ensure you have Python installed along with the required libraries:  

```bash
pip install torch numpy pandas matplotlib seaborn transformers scikit-learn
```
# OUTPUTS
* 102203339_topsis_result:Contains the ranking results.*
* 102203339_topsis_graph.png: A visualization of the ranking*

