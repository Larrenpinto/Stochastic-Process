# 📈 Financial Modelling Using Markov Chain

This project demonstrates how **Markov Chains** can be used to model and forecast gold price movements over time using historical data and Monte Carlo simulations. It blends the mathematical foundation of stochastic processes with real-world financial modeling.

---

## 📄 Abstract

This project explores the use of **Markov Chains** in financial modeling by simulating future gold price movements. Gold price returns are categorized into discrete states—up, down, and stable—to construct a transition probability matrix. Using this, 1000 future price paths are generated over a 6-year forecast horizon. The project visualizes the average and individual simulated paths, providing insights into long-term trends and market volatility. This method offers a practical and interpretable framework for forecasting and risk analysis in finance.

---

## 🔍 Introduction

Financial markets are inherently uncertain and governed by a combination of random fluctuations and observable trends. In this context, **Markov Chains** serve as a simple yet powerful tool to model the probabilistic transitions between market states. This project applies this concept to gold price data to forecast future price movements and understand potential risk scenarios.

---

## 🎯 Objective

- Model gold price fluctuations using a **Markov Chain framework**.
- Generate a **transition matrix** based on historical state transitions.
- Simulate **1000 possible future paths** using Monte Carlo simulation.
- Compare forecasts from **real** and **simulated** transition matrices.
- Visualize and interpret the average and individual forecast outcomes.

---

## 🛠️ Methodology

1. **Data Processing**  
   - Gold price changes are converted to discrete states: Up, Down, Stable.

2. **Transition Matrix Construction**  
   - Historical state transitions are used to compute a transition matrix.

3. **Simulation of Future Paths**  
   - 1000 future state sequences are generated based on the transition probabilities.
   - Each path covers 12 months (1 year).

4. **Mapping to Price Movements**  
   - States are converted to price changes: -1, 0, +1 and cumulatively summed.

5. **Visualization**  
   - Individual paths show volatility.
   - The average path reveals expected trend.

6. **Alternative Transition Matrix**  
   - A synthetic matrix is created from a simulated sequence for comparison.

---

## 📊 Results and Discussion

- **Simulated Paths**: Showed realistic variation, mimicking market volatility.
- **Average Forecast**: Displayed a slow upward trend in gold prices.
- **Model Comparison**: Real data transition matrix gave more consistent results than the synthetic one.
- **Key Insight**: Markov Chains effectively simulate a range of plausible futures without overfitting to one specific trend.

---

## 🧾 Conclusion

This study showcases the **effectiveness of Markov Chains** in modeling and forecasting financial time series. It emphasizes how a simple probabilistic model can provide valuable insights into market behavior. While it has limitations—like assuming constant probabilities and ignoring external factors—it lays a strong foundation for more advanced stochastic modeling in finance.

---

## ✅ Technologies Used

- Python (NumPy, Matplotlib)
- Jupyter Notebook
- Basic probability and stochastic processes
