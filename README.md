# Speaker Dialect Recognition Using Machine Learning Algorithms in WEKA

This project explores the application of machine learning techniques to recognize speaker dialects using a provided dataset. The algorithms are implemented using the WEKA software suite, and their performance is evaluated using 5-fold cross-validation.

## 👥 Authors
- Mariam Turk 
- Shahd Loai  


## 🧠 Project Summary
This experiment focuses on classifying dialects in a speech dataset using machine learning models. We preprocess the data in WEKA, apply classification algorithms, and evaluate their performance using standard metrics.

### 🛠 Tools Used
- **WEKA** (Waikato Environment for Knowledge Analysis): A powerful GUI-based machine learning suite
- **5-Fold Cross-Validation**: Used for performance evaluation

## 🗂️ Dataset
The dataset used is a **Speaker Dialect Recognition** dataset. It consists of pre-labelled speech samples from different dialects, formatted for classification in WEKA.

## 🧪 Algorithms Applied
### 1. Decision Tree (J48)
- **Default Settings Accuracy**: 76.59%
- **Modified (confidenceFactor = 0.1)**: 79.93%
- Metrics: Precision, Recall, F1-Score calculated and validated

### 2. Naïve Bayes
- **Default Settings Accuracy**: 78.57%
- **Modified (doNotCheckCapabilities = True)**: 77.68%
- Metrics include Precision, Recall, Accuracy, and F1-Score

### 3. Multi-Layer Perceptron (MLP)
- **Default Settings**: Results incomplete
- **Modified (momentum = 0.001)**: Results incomplete
- Additional tuning needed for meaningful evaluation

## 📊 Evaluation Metrics
Each algorithm was evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **True Positives / Negatives**
- **False Positives / Negatives**

## 🔄 Cross-Validation Method
- We used **5-fold cross-validation**, where the dataset is divided into 5 parts.
- Each part is used once as test data while the rest serve as training data.
- This approach ensures reliable performance estimates and reduces overfitting.

## 📈 Results Summary
| Algorithm       | Accuracy (Default) | Accuracy (Tuned) |
|----------------|--------------------|------------------|
| Decision Tree  | 76.59%             | 79.93%           |
| Naïve Bayes    | 78.57%             | 77.68%           |
| MLP            | Incomplete         | Incomplete       |

## ✅ Conclusion
- **Decision Tree** performs best after tuning with a confidence factor of 0.1.
- **Naïve Bayes** is simple and effective but not significantly improved by tuning.
- **MLP** needs further experimentation to fully evaluate its capabilities.

## 🔍 Future Work
- Complete MLP experimentation with proper parameter tuning
- Explore additional algorithms (e.g., Random Forest, SVM)
- Use a larger or more diverse dataset for broader generalization

## 📚 References
- WEKA Official Site: [https://www.cs.waikato.ac.nz/ml/weka/](https://www.cs.waikato.ac.nz/ml/weka/)
- "Data Mining: Practical Machine Learning Tools and Techniques" — Ian H. Witten et al.

## 📄 License
This project is for academic purposes only. All rights reserved to the authors.

