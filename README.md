# 🎵 Music Genre Classification using Deep Learning

A deep learning project that classifies music into different genres using neural networks, achieving 63% accuracy across 10 different music genres.

## 📊 Project Overview

This project uses deep learning to classify music into different genres:
- Blues
- Classical  
- Country
- Disco
- Hip-hop
- Jazz
- Metal
- Pop
- Reggae
- Rock

## 🔑 Key Results

- Overall Accuracy: 63%
- Best Performing Genres:
  - Metal: 96% precision, 92% recall
  - Classical: 81% precision, 100% recall 
  - Blues: 70% precision, 80% recall

## 📈 Model Performance

### Genre-wise Performance
```
              Precision    Recall  F1-score
Metal            0.96       0.92     0.94
Classical        0.81       1.00     0.90
Blues            0.70       0.80     0.74
Pop              0.71       0.77     0.74
Jazz             0.73       0.73     0.73
Country          0.64       0.52     0.57
Rock             0.50       0.62     0.55
Disco            0.45       0.48     0.47
Reggae           0.45       0.22     0.29
Hip-hop          0.30       0.40     0.34
```

## 🛠️ Technical Implementation

### Data Processing
- Audio feature extraction using librosa
- Data normalization and preprocessing
- Train-test split for model evaluation

### Model Architecture
- Neural network with multiple layers
- Early stopping to prevent overfitting
- Categorical cross-entropy loss function
- Adam optimizer

## 📦 Requirements
- librosa
- matplotlib 
- numpy
- pandas
- plotly
- scikit-learn
- tensorflow

## 🎯 Future Improvements
- Collect more training data
- Experiment with different model architectures
- Add attention mechanism
- Implement data augmentation
- Support more genres

---
Made with ❤️ by Amit Jangir
