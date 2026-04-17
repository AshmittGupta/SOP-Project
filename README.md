# 📊 EGARCH vs CoTAR/TAR — Geopolitical Risk & Commodity Volatility

A comprehensive empirical study comparing **EGARCH** and **CoTAR/TAR** frameworks to analyze how **Geopolitical Risk (GPR)** impacts **commodity market volatility** across 18 global commodity futures.

---

## 📌 Overview

This project investigates how geopolitical events influence commodity volatility using two complementary modeling approaches:

- **EGARCH (Exponential GARCH)** → captures *volatility level, persistence, and asymmetry*
- **CoTAR/TAR (Threshold Autoregression)** → captures *regime-switching behavior based on GPR*

📅 **Dataset Range:** January 2000 – March 2026  
📈 **Commodities Covered:** 18 (Energy, Metals, Agriculture)  

---

## 🧠 Key Research Questions

- Does geopolitical risk increase or stabilize volatility?
- Does GPR change volatility regimes or just its magnitude?
- Are effects different across commodity classes?

---

## ⚙️ Methodology

### 1. EGARCH Model
- Captures volatility clustering and asymmetry
- Measures persistence and GPR impact

### 2. CoTAR / TAR Model
- Captures regime-switching behavior
- Differentiates between low and high GPR regimes

---

## 📊 Key Findings

- **Precious Metals** → Safe-haven (volatility decreases under GPR)
- **Energy Markets** → Strong volatility increase under GPR
- **Agriculture & Metals** → Supply-chain driven volatility
- **WTI Oil, Zinc, Soybean** → Strong regime-switching behavior

---

## 📁 Repository Structure

```
├── MATLAB_Code/
├── Reports/
├── Data/
└── README.md
```

---

## 🚀 How to Run

1. Open MATLAB  
2. Navigate to project folder  
3. Run:
   ```matlab
   main_CoTAR.m
   main_TAR.m
   ```

---

## 👨‍💻 Author

**Ashmitt Gupta**  
BITS Pilani, Goa Campus  

---

## ⭐ Notes

- EGARCH → Best for volatility modeling  
- CoTAR → Best for regime detection  
- Combined → Most powerful insight  

---

## 🔥 Future Work

- Machine learning integration  
- High-frequency data analysis  
- Cross-market spillover effects  
