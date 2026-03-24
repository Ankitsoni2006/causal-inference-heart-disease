⭐ If you find this project useful, consider giving it a star!

# 🧠 From Correlation to Causation: Heart Disease Risk Analysis

## 🚀 Overview
Most machine learning models focus on prediction. But real-world decision-making—especially in healthcare—requires understanding **causation**.

This project applies **causal inference techniques** to uncover how clinical variables actually influence heart disease risk.


## 🎯 Objective
- Move beyond correlation-based insights  
- Estimate causal effects using structured frameworks  
- Simulate real-world interventions  



## 🧪 Key Concepts Used
- Directed Acyclic Graphs (DAGs)
- Confounding & Backdoor Adjustment
- do-Operator (Intervention Simulation)
- Average Treatment Effect (ATE)
- Individual Treatment Effect (ITE)
- Heterogeneous Treatment Effects



## 📊 Dataset
- ~1000 patient records  
- Binary target: heart disease (0/1)  
- Key variables:
  - `oldpeak` (treatment)
  - `age` (confounder)



## ⚙️ Methodology
1. Built causal DAG to model relationships  
2. Identified confounders (age)  
3. Compared:
   - Naive model
   - Adjusted model  
4. Simulated interventions using do-operator  
5. Estimated treatment effects  
6. Analyzed heterogeneity and interaction  
7. Validated using Random Forest  



## 📈 Key Insights
- Oldpeak has a **consistent causal effect**  
- Effect is strongest at lower values  
- Diminishing impact at higher levels (saturation)  
- Age shifts baseline risk but weak interaction effect  
- Causal analysis reveals deeper insights than correlation  



## ⚠️ Limitations
- Observational dataset (not causal ground truth)  
- Limited features  
- Results are not medically definitive  



## 💡 Key Takeaway
> Causal thinking transforms data analysis from prediction to decision-making.


## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn


## 📌 Project Highlights
- Built using causal inference (not just ML)
- Includes counterfactual reasoning
- Real-world healthcare application
- Research-style analysis and interpretation


## 👤 Author
**Ankit Soni**
