# Gradient Descent Optimization Study

A comprehensive study on various gradient descent optimization methods and their effects on convergence, with a focus on learning rate and batch size parameters.

## 📚 Study Overview

This project explores different variants of gradient descent algorithms applied to logistic regression, examining:


- Implementation of various optimization methods including:
  - Basic gradient descent
  - Stochastic gradient descent (SGD)  
  - Momentum
  - Nesterov accelerated gradient
  - AdaGrad
  - RMSprop
  - Adam
 - Ridge/Lasso regularization
 - The impact of learning rate on convergence
- The effect of batch size on stochastic gradient descent

## 🔧 Implementation Details

### Part 1: Optimization Methods
- Implementation of 8 different gradient descent variants
- Analysis of convergence properties
- Comparison of optimization speeds and stability
- Mathematical foundations explained for each method

### Part 2: Learning Rate Analysis
- Study of learning rate's impact on:
 - Convergence speed
 - Stability
 - Final accuracy
- Examination of under/over fitting scenarios
- Optimal learning rate determination

### Part 3: Batch Size Study
- Analysis of batch size impact on:
 - Training efficiency
 - Model performance
 - Computational costs
- SMOTE oversampling implementation
- Detailed performance metrics

## 📊 Experimental Results

Applied to real banking marketing dataset with:
- 41,188 samples
- 21 features
- Binary classification task (subscription prediction)

### Key Findings:
- Adam optimizer showed fastest convergence
- SGD demonstrated best recall performance
- All methods achieved >80% accuracy
- RMSprop exhibited some instability issues
- Learning rate of 0.05 proved optimal for most methods

## 🔬 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 📈 Performance Metrics

| Method | Accuracy | Precision | Recall | F1 Score |
|--------|----------|-----------|---------|-----------|
| GD | 0.840037 | 0.888294 | 0.778111 | 0.829560 |
| SGD | 0.828825 | 0.833620 | 0.821889 | 0.827713 |
| Adam | 0.836060 | 0.881318 | 0.776938 | 0.825843 |
| RMSprop | 0.808226 | 0.944246 | 0.655375 | 0.773727 |

## 🎯 Conclusions

- Adaptive methods (Adam, RMSprop) showed best convergence speed
- SGD achieved highest recall, crucial for avoiding false negatives
- Batch size significantly impacts training stability and efficiency
- Regularization methods help prevent overfitting

## 🤝 Authors

- Mehdi Mansour

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
