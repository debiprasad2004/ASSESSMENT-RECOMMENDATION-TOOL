# ASSESSMENT-RECOMMENDATION-TOOL

🔍 Goals Fine-tune a lightweight LLM (TinyLlama) on a structured dataset of CS multiple-choice questions.

Evaluate model performance on question generation and answer selection tasks.
Visualize training metrics and log evaluation results.
🧪 Training Procedure Model: TinyLlama-1.1B-Chat Tokenizer: AutoTokenizer from Hugging Face Loss Function: Cross-entropy (labels = input IDs) Epochs: 3 Batch Size: 4 Evaluation: Accuracy, BLEU score

📈 Results You can find training logs and loss plots in the logs/ folder. Sample plot (Training Loss vs Steps):

🧪 Evaluation Metrics include: Accuracy of model on test MCQs BLEU for comparing paraphrased questions Example: python BLEU score: 0.67 Accuracy: 84.2%

