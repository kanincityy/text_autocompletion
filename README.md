# Character-Level Text Auto-Completion with LSTMs

This project implements a **character-level LSTM model** for predicting the next three characters in a sequence — mimicking auto-suggestion features found in text editors or mobile keyboards (e.g., `"Merry Christ…" → "mas"`).

> Developed as part of my MSc in Language Sciences coursework @ UCL.

---

## Project Objective

- Train an LSTM model to predict the next **3 characters** in a sequence  
- Use a corpus of **7 literary texts** from Project Gutenberg  
- Handle preprocessing, sequence slicing, tokenization, and model training  
- Explore architecture choices, hyperparameters, and evaluate model behavior  
- Reflect on potential extensions or improvements

---

## Key Features

- **Data Preprocessing**: Cleaned and segmented character sequences from long-form text  
- **Model Architecture**: Implemented a multi-layer **LSTM** network with embedding + dropout  
- **Custom Dataset**: Built a `CharDataset` class for efficient mini-batch generation  
- **Training Pipeline**: Wrote training/validation loop using PyTorch  
- **Hyperparameter Exploration**: Tuned embedding size, hidden units, learning rate, and context window  

---

## 🛠Technologies Used

| Tool/Library   | Purpose                            |
|----------------|-------------------------------------|
| Python         | Core language                       |
| PyTorch        | Model building and training         |
| NumPy          | Tensor operations                   |
| NLTK           | Text cleaning/tokenization          |
| Google Colab   | Cloud environment for experiments   |

---

## Code Access

- **Colab Notebook**: [Character-Level LSTM Implementation](https://colab.research.google.com/drive/1QvOkBVqyNy3wFoFEryN4ubcoUp_XtUmC?usp=sharing)  
- **Model Checkpoints**: Located in `/model/` directory  

---

## Project structure

```
char_lstm_text_autocompletion/
├── model/ # Saved model weights
├── src/ # Training and dataset scripts (if split out)
├── README.md # This file
├── LICENSE # MIT License
└── [notebook].ipynb # Main implementation in Colab
```

---

## Reflections

This project taught me how to:
- Handle **sequence modeling** at the character level (vs. word-level NLP)  
- Design **custom training loops** in PyTorch  
- Think critically about **input/output alignment**, padding, and batch generation  
- Understand **temporal dependencies** and limitations of LSTMs in text generation

---

## 📄 License

Licensed under the **MIT License** — see the `LICENSE` file for full terms.

---

## Author

**Tatiana Limonova**  
*MSc Language Sciences (Technology of Language and Speech) – UCL*  
[GitHub](https://github.com/kanincityy) • [LinkedIn](https://www.linkedin.com/in/tatiana-limonova/)

---

Thanks for reading & happy coding! ✨🐇

