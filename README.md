# 🧠 Demand Prediction for Algorithmic & Dynamic Pricing  
### Using Principal Components and Perceptrons

> *"Where data meets decision — forecasting demand to power intelligent pricing."*

---

## 🚀 Project Overview
This project focuses on forecasting demand as a core component of **dynamic and algorithmic pricing strategies**.  
Using the **Walmart Kaggle dataset**, I applied deep learning and statistical methods to model **department-level sales** across multiple stores, addressing challenges such as **holiday markdowns** and the gap between observed sales and true latent demand.

While this analysis concentrates on **predictive modeling** rather than full prescriptive price optimization, it lays the groundwork for **integrating demand forecasts into data-driven pricing systems** in retail and e-commerce.

---

## 🧩 Takeaways

**Key highlights:**
- Connected **demand forecasting** to business applications like **dynamic pricing**  
- Applied statistical and ML techniques — **PCA**, **Perceptron**, **Gradient Descent** variants  
- Implemented and trained neural networks in **TensorFlow/Keras**  
- Tackled **high-dimensional data** and **external shocks** (holidays, promotions)  

> Together, these approaches demonstrate how machine learning can bridge predictive accuracy and business strategy.

---

## 🔬 Concepts Explored
- **Representation Learning:** Feature extraction and dimensionality reduction with PCA  
- **Learning Algorithms:** Perceptron (single-layer neural network as linear regression)  
- **Optimization:** Gradient Descent, Stochastic Gradient Descent (SGD), Mini-batch training  
- **Deep Learning Fundamentals:** TensorFlow/Keras implementation and activation functions  
- **Learning Dynamics:** Understanding how weights adapt to temporal demand patterns  

---

## 💡 Conceptual Summary & Business Impact

The project connects **machine learning theory** to **managerial decision-making**.

**Principal Component Analysis (PCA)** distills hundreds of correlated retail variables—holidays, promotions, seasonality—into a smaller, interpretable set of components.  
This dimensionality reduction makes models faster, more stable, and easier to explain—vital for leaders who need transparency, not just accuracy.

A **Perceptron-based neural network (Keras Sequential)** captures **nonlinear relationships** in demand such as threshold effects or diminishing returns from discounts.  
This yields more reliable forecasts during volatile periods (e.g., holidays, supply shocks).

In business terms, these methods support **algorithmic and dynamic pricing**:
- 🏬 **Reduce overstock & stockouts** through accurate demand planning  
- 💰 **Maximize revenue** by adjusting prices dynamically using elasticity estimates  
- 🤝 **Improve customer satisfaction** by maintaining consistent availability  

> Ultimately, demand modeling transforms pricing from intuition-driven to **data-driven decision systems** — enabling firms to balance **profitability, competitiveness, and customer trust** in real time.

---

## ⚙️ Technical Summary

**Pipeline**
1. Data preprocessing & feature engineering  
2. **PCA** for dimensionality reduction and noise filtering  
3. **Perceptron (Keras Sequential)** model for nonlinear regression  
4. **Gradient Descent** variations (batch, stochastic, mini-batch)  
5. **Evaluation:** baseline vs. neural models under time-based cross-validation  

**Tools**
> Python · Pandas · NumPy · Scikit-learn · TensorFlow/Keras · Matplotlib · Seaborn  

---

## 📊 Results
- PCA improved model efficiency and mitigated multicollinearity  
- Neural network captured nonlinearities better than linear baselines  
- Metrics (RMSE, MAPE) improved particularly during volatile holiday weeks  
- Forecast vs. actual plots showed interpretable residual patterns  

---

## 🧭 Business Link
The forecasting model serves as a **decision-support tool**, not a black box.  
By simulating how price or promotion changes influence demand, it forms the analytical foundation for **algorithmic pricing optimization** and **revenue management**.

This allows for controlled, data-driven pricing experimentation before deploying large-scale automation.

