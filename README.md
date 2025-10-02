# Engineering Probability and Statistics (EPS) - Course Assignments

This repository contains four computer assignments (CA0-CA3) for the Engineering Probability and Statistics course. Each assignment explores different aspects of probability theory, statistics, and their applications in machine learning and data analysis.

## 📚 Overview

The assignments progress from basic statistical analysis and text classification to advanced probability distributions and machine learning applications, providing a comprehensive practical foundation in probability and statistics.

## 📁 Assignment Details

### CA0: Text Classification using Naive Bayes
**Focus**: Natural Language Processing and Probabilistic Text Classification

**Description**: Implementation of a Naive Bayes classifier for Persian book categorization. 
**Key Components**:
- **Data Processing**: Persian text preprocessing using Hazm library
- **Feature Engineering**: Bag-of-words representation
- **Probability Calculations**: Implementation of Naive Bayes with additive smoothing
- **Model Variants**: Multiple implementations including bonus features for stopword removal and stemming

**Files**:
- `CA0_normal.py`: Basic Naive Bayes implementation
- `CA0_bonus_stopwords.py`: Implementation with stopword removal
- `CA0_stemming_bonus.py`: Implementation with stemming
- `CA0_both_bonuses.py`: Implementation with both stopwords and stemming
- `wo_additive_*.py`: Versions without additive smoothing
- `books_train.csv`, `books_test.csv`: Training and testing datasets

### CA1: Probability Distribution Analysis
**Focus**: Theoretical vs. Practical Distribution Analysis

**Description**: Comprehensive analysis of probability distributions through simulation and theoretical calculations. Students explore the convergence of empirical results to theoretical expectations.

**Key Topics**:
- **Binomial Distribution**: Analysis of mean and variance for different probability parameters
- **Statistical Convergence**: Comparison between theoretical and empirical results
- **Data Visualization**: Creating plots to visualize distribution properties
- **Simulation Methods**: Monte Carlo simulation techniques

**Exercises**:
- `ex1.ipynb`: Binomial distribution analysis with theoretical vs. practical comparison
- `ex2.ipynb`: Advanced probability calculations
- `ex3.ipynb`: Distribution parameter estimation
- `ex3_bonus.ipynb`: Bonus exercises with extended analysis
- `ex4.ipynb`: Complex probability scenarios

### CA2: Poisson Distribution and Statistical Modeling
**Focus**: Poisson Processes and Real-world Data Analysis

**Description**: Analysis of transportation data using Poisson distribution. The assignment uses real data from Tehran's public transportation system (Metro and BRT).

**Key Components**:
- **Poisson Distribution**: Parameter estimation and model fitting
- **Data Analysis**: Statistical analysis of Metro and BRT passenger data
- **Hypothesis Testing**: Validation of Poisson model assumptions
- **Visualization**: Histogram analysis and probability mass function plotting
- **Distribution Addition**: Analysis of sum of independent Poisson variables

**Datasets**:
- `Tarbiat.csv`: Transportation data with Metro and BRT passenger counts
- `digits.csv`: Additional dataset for statistical analysis

**Exercises**:
- `ex1.ipynb`: Poisson parameter estimation and visualization
- `ex2.ipynb`: Distribution fitting and hypothesis testing
- `ex3.ipynb`: Advanced Poisson modeling

### CA3: Machine Learning and Advanced Statistical Analysis
**Focus**: Deep Learning, Autoencoders, and Statistical Analysis of High-dimensional Data

**Description**: Advanced assignment combining machine learning with statistical analysis. Uses pre-trained autoencoder models and real-world datasets for comprehensive analysis.

**Key Components**:
- **Autoencoder Analysis**: Working with MNIST digit reconstruction
- **Error Analysis**: Mean Squared Error (MSE) distribution analysis
- **Sports Analytics**: Statistical analysis of FIFA 2020 player data
- **Deep Learning**: Understanding neural network outputs through statistical lens
- **High-dimensional Data**: Handling and analyzing complex datasets

**Datasets and Models**:
- `mnist/`: MNIST handwritten digit data (x_train, y_train, x_test, y_test)
- `mnist_AE.h5`: Pre-trained autoencoder model
- `FIFA2020.csv`: Comprehensive FIFA player statistics dataset

**Exercises**:
- `ex1.ipynb`: Autoencoder reconstruction analysis and MSE distribution
- `ex2.ipynb`: FIFA player data statistical modeling
- `ex3.ipynb`: Advanced machine learning statistical analysis

## 🛠️ Technical Requirements

### Dependencies
- **Python 3.x**
- **Data Analysis**: pandas, numpy
- **Visualization**: matplotlib
- **Machine Learning**: keras, tensorflow
- **Statistics**: scipy.stats
- **Persian NLP**: hazm (for CA0)
- **Progress Tracking**: alive_progress

### Installation
```bash
pip install pandas numpy matplotlib scipy keras tensorflow hazm alive-progress
```

## 📊 Learning Outcomes

Through these assignments, students develop proficiency in:

1. **Probability Theory**: Understanding and applying fundamental probability concepts
2. **Statistical Analysis**: Performing hypothesis testing and parameter estimation
3. **Data Science**: Processing and analyzing real-world datasets
4. **Machine Learning**: Understanding statistical foundations of ML algorithms
5. **Programming**: Implementing statistical algorithms from scratch
6. **Visualization**: Creating meaningful statistical plots and visualizations

## 📈 Assignment Progression

The assignments are designed with increasing complexity:

- **CA0**: Introduction to probabilistic thinking through text classification
- **CA1**: Foundational probability distributions and simulation
- **CA2**: Real-world data analysis and Poisson processes
- **CA3**: Advanced applications combining ML and statistics

## 🔍 Key Statistical Concepts Covered

- **Probability Distributions**: Binomial, Poisson, Normal
- **Bayesian Statistics**: Naive Bayes classification
- **Parameter Estimation**: Maximum likelihood and method of moments
- **Hypothesis Testing**: Goodness of fit tests
- **Error Analysis**: MSE and statistical significance
- **Convergence**: Law of large numbers and central limit theorem
