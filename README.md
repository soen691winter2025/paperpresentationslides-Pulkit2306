# 📌 An Analysis of Patch Plausibility and Correctness  

## 📖 Overview  
This repository contains a **paper presentation** on  
*"An Analysis of Patch Plausibility and Correctness for Generate-and-Validate Patch Generation Systems"*,  
authored by **Zichao Qi, Fan Long, Sara Achour, and Martin Rinard**.  

The presentation explores **automated patch generation**, focusing on:  
- 🚀 **Limitations** of existing patching systems (GenProg, RSRepair, AE).  
- 🛑 **Weak validation proxies** in automated patch repair.  
- 🔍 **Kali**, a **functionality deletion-based approach** that simplifies patch generation while achieving similar or better correctness rates.  

---

## 🚀 Key Insights from the Paper  
✅ **Problem:**  
Most automated patching systems generate **incorrect but plausible patches** due to **weak validation criteria**.  

✅ **Findings:**  
🔹 **94.5% of GenProg patches were plausible but incorrect**, leading to security risks. *(Page 30, Figure 1)*  

✅ **Solution:**  
💡 **Kali**, a **functionality deletion-based patching system**, matched or outperformed GenProg, RSRepair, and AE in producing correct patches.  

---

## 📊 Experimental Results Summary  
| **Patch System** | **Correct Patches Found** | **Plausible Patches (Incorrect Fixes)** |  
|-----------------|-------------------------|--------------------------------|  
| **GenProg**     | 2/105 (1.9%)            | 104/110 (94.5%)               |  
| **RSRepair**    | 2/24 (8.3%)             | 37/44 (84%)                   |  
| **AE**          | 3/105 (2.9%)            | 22/27 (81.5%)                 |  
| **Kali**        | 3/105 (2.9%)            | 27/27 (100%) (All correct)    |  

📊 *Data extracted from Figure 1, Page 30 of the paper.*  

---

## 📌 Key Topics Covered  
- 🔍 **Weak Proxies in Patch Validation**  
- 🔥 **Security Risks in Automated Repair**  
- 📊 **Correct vs. Plausible Patches – Data-Driven Analysis**  
- ✅ **Evaluation of Kali vs. GenProg, RSRepair, and AE**
  
---

## 🎯 Future Enhancements  
✅ **Add interactive visuals** (e.g., Python-based charts) for better understanding.  
✅ **Extend the analysis to non-C languages** (e.g., Java, Python).  
✅ **Explore improvements in test validation beyond weak proxies.**  

---

### 🛠 Maintained by: **Pulkit Bansal - 40321488 - Concordia University**  

---
