# -Interactive-logistic-growth-simulator
# Interactive Logistic Growth Simulator — Population & Growth Rate Visualization

An educational, client‑ready simulator demonstrating the **logistic growth model** with interactive sliders, dual plots (Population and ΔP), and inflection point annotations at P = K/2.

---

## 🚀 Features
- **Interactive sliders** for growth rate (r), carrying capacity (K), initial population (P0), and time horizon (t_max).  
- **Dual plots**:
  - Population curve (S‑shaped) approaching carrying capacity.  
  - ΔP curve (growth rate per step), peaking at **P = K/2** (the inflection point).  
- **Inflection point annotation** highlights where growth is fastest.  
- **Error handling** warns if parameters are unrealistic (e.g., P0 > K).  
- **Clean dashboard layout** for client‑facing presentations.

---

## 🎯 Try It Yourself
Click below to open the notebook in Google Colab and run the simulation interactively:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/logistic-growth-simulator/blob/main/Logistic_Growth_Simulator.ipynb)

---

## 📊 Preview
Here’s what the simulator looks like:

![Dashboard](images/dashboard.png)  
![Curves with K/2 annotation](images/curves.png)

---

## 📘 Applications
- **Biology**: population dynamics and resource competition  
- **Business**: forecasting user adoption or product diffusion  
- **Economics**: market saturation and resource limits  

---

## 🔮 Next Steps
Potential extensions include:
- Adding **stochastic variation** for random shocks.  
- Modeling **multiple interacting populations** (predator–prey).  
- Integrating with **real datasets** for validation.  
- Building a **dashboard interface** for client‑facing presentations.  

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/logistic-growth-simulator.git
cd logistic-growth-simulator
pip install -r requirements.txt
jupyter notebook
