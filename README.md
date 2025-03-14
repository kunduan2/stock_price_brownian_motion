# Stock Price Movement Simulation Using Brownian Motion

This project aims to explore the role of **Brownian Motion (BM)** in simulating stock price movement. Below are the steps and methodologies we used to model and analyze the behavior of stock prices based on Brownian motion:

### **1. Initial Simulation with Brownian Motion**

1a. **File: `filename_vr1.ipynb`**
   - We use the **matrix method** to simulate the effects of **2000 Brownian motions (BM)**.
   - We show that the simulated BMs are nearly normally distributed at each time step, by focusing on the distribution at the **end time**.

1b. **Adding Drift to the Model**
   - To make the model more realistic, we introduce a **'drift' term** in the simulation.
   - This addition shifts the **mean** of the distribution at each time step, moving it away from zero, reflecting real-world stock price behavior more accurately.

### **2. Future Work**

2a. In the next commit, we plan to **extend the model** by incorporating additional terms to further refine the simulation and enhance its predictive accuracy.

