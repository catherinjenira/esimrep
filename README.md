# 8-Input AND Gate Implementation Using 2-Input AND Gates

## 🧠 Project Overview
This project demonstrates how an **8-input AND gate** can be designed and simulated using only **2-input AND gates** in **Proteus**.  
It highlights the modular approach in digital logic design—showing how complex logic functions can be built from simpler building blocks.

---

## 🎯 Objective
To design, simulate, and verify the working of an **8-input AND gate** using hierarchical connections of basic 2-input AND gates.

---

## ⚙️ Circuit Description
The circuit is designed in three levels:
1. **Level 1:** Four 2-input AND gates combine the 8 inputs in pairs (A·B, C·D, E·F, G·H).  
2. **Level 2:** The four outputs from Level 1 are combined into two outputs using two more AND gates.  
3. **Level 3:** The final two outputs are ANDed again to produce a single output — the result of all 8 inputs ANDed together.

🧩 **Logic Function:**  
\[
Y = A \cdot B \cdot C \cdot D \cdot E \cdot F \cdot G \cdot H
\]

---

## 🔬 Simulation Results
| Input Condition | Expected Output | Observed Output |
|------------------|----------------|----------------|
| All inputs = 1 | 1 | ✅ 1 |
| Any input = 0 | 0 | ✅ 0 |

The simulation confirms that the circuit behaves exactly like an ideal 8-input AND gate.

---

## 🧾 Files Included
