# Monte Carlo Simulation – Newspaper Vendor Problem (Python)

This project simulates the **newspaper vendor problem** using a **Monte Carlo approach** in Python.  
It estimates the average and maximum profit based on random daily demand influenced by the type of news (Good, Fair, or Poor).

---

## 🎯 Objective
A vendor must decide how many newspapers to stock each day given uncertain demand.  
This simulation helps estimate profit under stochastic (random) demand, considering:
- Probabilities of different news conditions  
- Variable daily demand for each condition  
- Fixed selling price, cost, and scrap value

---

## 🧮 Model Parameters
| Parameter | Description | Value |
|------------|--------------|--------|
| `g_avg` | Probability of good news | 0.35 |
| `f_avg` | Probability of fair news | 0.45 |
| `p_avg` | Probability of poor news | 0.20 |
| `supply` | Newspapers stocked per day | 70 |
| `s` | Selling price per paper | \$0.50 |
| `c` | Cost per paper | \$0.33 |
| `Ex` | Expected overhead cost per paper | \$0.17 |
| `Sc` | Scrap value per unsold paper | \$0.05 |

---

## ⚙️ Simulation Details
- Number of simulations: **500**
- Days per simulation: **20**
- Demand ranges by news type:
  - Good: 40–70  
  - Fair: 30–60  
  - Poor: 20–50  

Each simulation computes total profit over 20 days and records it.  
The program outputs the **average profit** and **maximum profit** across all simulations.

---

## 🧰 Requirements
Install dependencies with:
```bash
pip install numpy
```
▶️ Run the Simulation
Run the script using:
```bash
python newspaper_vendor_simulation.py
```
📊 Concepts Demonstrated
- Monte Carlo simulation
- Demand forecasting under uncertainty
- Probability-based decision analysis
- Profit optimization for inventory management
