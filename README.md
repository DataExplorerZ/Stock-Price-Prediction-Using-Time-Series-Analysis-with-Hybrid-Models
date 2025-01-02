# Stock Price Prediction Using Time Series Analysis with Hybrid Models

This repository contains the implementation of **Stock Price Prediction Using Time Series Analysis with Hybrid Models**, a project aimed at analyzing and predicting stock prices using advanced deep learning architectures like LSTM with Attention Mechanisms, CNN-LSTM Hybrid, and Bidirectional LSTM.

## Project Overview

The project explores the application of deep learning for predicting stock prices, which is inherently challenging due to the volatile and noisy nature of financial data. By leveraging historical S&P 500 stock data, the research compares traditional methods with hybrid models to evaluate their performance in financial forecasting.

### Key Features
- **Deep Learning Models**:
  - LSTM with Attention
  - CNN-LSTM Hybrid
  - Bidirectional LSTM
- **Time Series Analysis**: Incorporates techniques like Moving Averages and Volume Analysis.
- **Data-Driven Insights**: Focuses on identifying short-term volatility and long-term trends.
- **Performance Metrics**: Evaluates models using MAE, MSE, and RMSE.

### Research Contributions
- Demonstrates the enhanced predictive capability of hybrid deep learning models.
- Addresses challenges like model interpretability, overfitting, and noisy data.
- Highlights the potential for improving financial decision-making through AI.

## Dataset

The dataset used is the **S&P 500 Stock Data**, obtained from Kaggle. It contains historical stock prices for all companies in the S&P 500 index over a five-year period, including columns for date, open, high, low, close, and volume.

Dataset Source: [S&P 500 Stock Data on Kaggle](https://www.kaggle.com/datasets/camnugent/sandp500?resource=download).

## Methodology

1. **Data Preprocessing**:
   - Handling missing values, feature engineering, and normalization.
   - Generating new features like Daily Range and Simple Moving Averages.

2. **Model Development**:
   - Training LSTM, CNN-LSTM, and Bi-LSTM models.
   - Incorporating Attention Mechanisms to improve feature importance.

3. **Evaluation**:
   - Comparing models using standard metrics (MAE, MSE, RMSE).
   - Analyzing predicted vs actual values to assess model accuracy.

## Results

- **LSTM with Attention**: Captured long-term dependencies effectively.
- **CNN-LSTM Hybrid**: Balanced short-term and long-term trend analysis.
- **Bidirectional LSTM**: Outperformed other models in capturing past and future dependencies.

## Challenges

- High computational complexity and potential overfitting.
- Difficulty in interpreting deep learning model predictions.
- Dependency on high-quality, comprehensive datasets.


## Technologies Used

- **Programming Language**: Python
- **Frameworks/Libraries**: TensorFlow, PyTorch, Scikit-learn, Pandas, Matplotlib
- **Tools**: Kaggle, Google Colab, VS Code

## Future Work

- Incorporate Explainable AI (XAI) methods to enhance model interpretability.
- Extend to cross-market and international applications.
- Explore advanced models like GANs and Reinforcement Learning.

## License

This project is licensed under the MIT License.

## Contact

For further details or queries, feel free to contact:
**Zeeshan Ali**
Email: zeeshanali22pch@gmail.com
