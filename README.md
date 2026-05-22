# Task 1: News Topic Classifier Using BERT

**Objective:** Fine-tune BERT to classify news headlines 
into topic categories.

**Dataset:** AG News Dataset (HuggingFace) — 120,000 articles

**Model:** bert-base-uncased (Fine-tuned)

**Categories:** World, Sports, Business, Sci/Tech

**Key Results:**
- Accuracy: 88.8%
- F1 Score: 88.8%
- Sci/Tech & Sports predictions: 99% confidence
- Trained on 3,000 examples for 3 epochs on T4 GPU

**Tools Used:** Python, HuggingFace Transformers, 
BERT, PyTorch, Scikit-learn, Google Colab T4 GPU

## How to Run
1. Open notebook in Google Colab
2. Enable T4 GPU runtime
3. Run all cells
