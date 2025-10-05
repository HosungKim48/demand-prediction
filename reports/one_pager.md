# Demand Prediction — One Pager

**Objective:** Support algorithmic and dynamic pricing through accurate demand forecasting.  

**Data:** Walmart weekly sales data across multiple stores and departments, augmented with calendar and event-based features (holidays, promotions, markdowns).  

**Methods:**
- **Principal Component Analysis (PCA)** for dimensionality reduction and noise filtering.  
- **Perceptron (Keras Sequential)** model for nonlinear demand prediction.  
- **Gradient Descent variants** (batch, stochastic, mini-batch) for training stability.  
- **Time-based cross-validation** to prevent data leakage.  

**Key Insights:**
- PCA improved model efficiency and interpretability.  
- Neural network captured nonlinear demand effects missed by linear models.  
- Forecast accuracy (RMSE, MAPE) improved during high-variance holiday periods.  

**Business Relevance:**
- Enables **data-driven pricing decisions** and **revenue optimization**.  
- Helps firms reduce **overstock and stockouts**, improving customer experience.  
- Provides foundation for **algorithmic pricing engines** and **elasticity modeling**.  

**Next Steps:**
- Extend to product- or region-level forecasting.  
- Integrate price elasticity simulations for prescriptive analytics.  
- Add uncertainty quantification to support risk-aware pricing.  
