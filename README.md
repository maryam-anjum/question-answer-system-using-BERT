Question Answering Application
Description:
This project implements a question-answering model using the BERT transformer architecture. The application is trained to extract answers from a given context based on user queries.

Technologies Used:

Python
BERT-based model from SimpleTransformers
JSON for data handling
Model training and evaluation with custom training arguments
WandB for experiment tracking
Key Features:

Custom training and evaluation on JSON-based datasets using pre-trained BERT (bert-base-cased).
Fine-tuned for question-answering tasks using a dataset consisting of context and question-answer pairs.
Advanced model training configuration with batch size, evaluation steps, and sequence length adjustments.
Achieved prediction results on a variety of question types (e.g., factual, inference-based).
Results:

The model provides correct and similar answer predictions for test queries.
Evaluation metrics: Loss = 0.0369, 3 similar predictions, 0 incorrect.
