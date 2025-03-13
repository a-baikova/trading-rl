# 📈 Algorithmic Trading with Reinforcement Learning

## 📝 Project Overview  
This academic group project explores the application of **Reinforcement Learning (RL)** and statistical models to develop automated trading strategies for **Coca-Cola stock (KO)**. The goal was to maximize portfolio returns by leveraging historical market data and advanced machine learning techniques.

![image](https://github.com/user-attachments/assets/81923145-593a-40ca-9ba5-6d05bf834aac)

## 💡 Methodology  
- **Data Extraction**: Historical stock data was obtained using the `yfinance` library for the period between January 2019 and October 2024.  
- **Statistical Models**: Implemented **Exponential Moving Average (EMA)** and **Relative Strength Index (RSI)** to identify trading signals.  
- **Reinforcement Learning Models**: Developed RL algorithms, including **Q-Learning** and **Advantage Actor-Critic (A2C)**, to optimize buy/sell decisions in a simulated trading environment.  
- **Evaluation Metrics**: Performance was assessed using metrics such as Sharpe Ratio, Cumulative Returns, and CAGR.  

## 📊 Tools & Libraries  
- Python  
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`, `yfinance`, `gym`, `matplotlib`  

## 🔍 Results  
Of all the algorithms tested, the one with the best return values was the RSI (Relative Strength Index), with the highest value of the three main metrics: Sharpe Ratio, CAGR and Cumulative Returns. However, there were models with lower risk (variance and CVaR), such as Q-Learning using EMA.  
