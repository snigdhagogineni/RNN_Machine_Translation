# Neural Machine Translation using RNNs

## 📌 Project Overview
This project focuses on building a Neural Machine Translation (NMT) system using Recurrent Neural Networks (RNNs) to convert English sentences into French. The system leverages an encoder-decoder architecture with attention mechanisms to improve translation quality. The model is trained on a parallel corpus and showcases the power of sequence-to-sequence models in NLP tasks.

## 🧠 Key Features
- Implemented encoder-decoder architecture using RNN (GRU/LSTM).
- Applied attention mechanism for better context translation.
- Tokenization, padding, and vocabulary creation for English-French datasets.
- Model trained using teacher forcing and evaluated with BLEU score.

## 🔧 Tech Stack
- Python
- TensorFlow / PyTorch (based on implementation)
- NumPy
- Matplotlib (for training visualization)
- NLTK (optional for tokenization)

## 📁 Project Structure
```
├── data/                  # Contains the English-French dataset
├── models/                # Stores trained model checkpoints
├── notebooks/             # Jupyter Notebooks for EDA and training
├── src/
│   ├── dataloader.py      # Handles data preprocessing
│   ├── model.py           # Encoder, Decoder, Attention classes
│   └── train.py           # Model training logic
├── utils/                 # Utility functions for evaluation, BLEU, etc.
└── README.md              # Project documentation
```

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Prepare dataset (see `data/README.md` for instructions).
4. Run training:  
   `python src/train.py`
5. Evaluate translations:  
   `python src/evaluate.py`

## 📊 Results
- Training Accuracy: ~90%
- BLEU Score: ~0.65
- Improved accuracy with attention over basic RNN

## 📚 Learnings
- Gained hands-on experience in implementing RNNs from scratch.
- Understood encoder-decoder and attention mechanism behavior.
- Developed pipeline from data preprocessing to model evaluation.

