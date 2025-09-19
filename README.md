# Character-level Language Models

This project explores **statistical and neural approaches to language modeling** at the character level.  
The dataset consists of city names, and the goal is to train models that can **learn character distributions and generate plausible new names**.

## Features
- **Unigram, Bigram, and Trigram Models**  
  - With add-k (Laplace) smoothing and interpolation  
- **Smoothed Language Models**  
  - Unigram with Add-1 smoothing  
  - Bigram with Add-k and interpolation  
  - Trigram with interpolation  
- **Neural Models**  
  - Feed-forward Neural Network (Neural n-gram LM)  
  - Recurrent Neural Network (RNN LM)  
- **Evaluation Metrics**  
  - Log-likelihood, perplexity, and KL divergence  
- **Name Generation**  
  - Sampling from probability distributions  
  - Conditional generation given prefixes  

## Results
- Compared classical n-gram models vs. neural language models
- Evaluated on training and validation sets
- Generated diverse city-like names with varying quality depending on the model

## Technologies
- Python (3.9+)  
- PyTorch  
- Torchtext  
- Pandas, NumPy, Matplotlib  

## How to Run
```bash
# Install dependencies
pip install torch==2.3.0 torchtext==0.18 pandas numpy matplotlib

# Run the Python script
python nlp_assignment2.py
```

## Author
**Siddharth Jain**  
M.Tech Research in Robotics and Autonomous Systems, IISc Bengaluru
