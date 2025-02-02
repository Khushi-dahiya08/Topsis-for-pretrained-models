# Topsis-for-pretrained-models
# Chatbot Model Evaluation using TOPSIS

# Overview

* This project evaluates different chatbot models using the TOPSIS ranking method based on three key factors:

Average Similarity Score - Measures how similar chatbot responses are.

Inference Speed - Simulated processing speed of the model.

Model Size - Simulated storage size of the model. *

Models Used

The following pre-trained models were evaluated:

Model Name

Type

EleutherAI/gpt-neo-125M

Small GPT-Neo

microsoft/DialoGPT-medium

Medium DialoGPT

facebook/blenderbot-400M-distill

Distilled BlenderBot

Installation & Dependencies

Ensure you have Python installed along with the required libraries:

pip install torch numpy pandas matplotlib seaborn transformers scikit-learn

Running the Script

To execute the chatbot evaluation, run:

python chatbot_evaluation.py

Outputs

chatbot_topsis_results.csv: Contains the ranking results.

chatbot_topsis_graph.png: A visualization of the ranking.

Sample Visualization
