# 8-Input AND Gate Implementation Using 2-Input AND Gates

## 🧠 Project Overview
This project demonstrates how an **8-input AND gate** can be designed and simulated using only **2-input AND gates** in **eSim by FOSSEE (IIT Bombay)**.  
It showcases the hierarchical construction of digital logic circuits using basic logic components.

---

## 🎯 Objective
To design, simulate, and verify the operation of an **8-input AND gate** using multiple **2-input AND gates** in eSim.  
This project helps understand modular logic design and the concept of scalability in digital systems.

---

## ⚙️ Circuit Description
The circuit is structured in **three hierarchical levels**:

1. **Level 1:** Four 2-input AND gates combine 8 inputs into 4 outputs (A·B, C·D, E·F, G·H).  
2. **Level 2:** Two 2-input AND gates combine the four outputs into two signals.  
3. **Level 3:** A final 2-input AND gate combines these two signals to generate the overall output.

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

The simulation verifies that the output is HIGH only when all eight inputs are HIGH, confirming the correct AND logic functionality.

---

## 🧾 Files Included
/schematic/ → eSim project files (.sch)
/simulation/ → Output screenshots and test results
/report/ → Project report (PDF)
/README.md → Project documentation

---

## 🧰 Tools & Software
- **eSim (by FOSSEE, IIT Bombay)**
- **NgSpice Simulator**
- **KiCad (for schematic design)**
- **Digital Logic Design concepts**

---

## 🚀 How to Run
1. Open the `.sch` file in **eSim**.  
2. Connect the logic input sources (1 for HIGH, 0 for LOW).  
3. Run the simulation using **NgSpice** within eSim.  
4. Observe the final output — it will be HIGH only when all eight inputs are HIGH.

---

## 🧑‍💻 Author
**Catherin Jenira**  
BE Computer Science and Engineering  
Rajalakshmi Institute of Technology  

---

## 🌐 GitHub Repository
[🔗 View Project on GitHub](https://github.com/username/8-Input-AND-Gate-eSim-Project)

*(Replace the above link with your actual GitHub URL once uploaded.)*

---

## 🏁 Conclusion
The project successfully demonstrates the design and simulation of an **8-input AND gate** using **2-input AND gates** in **eSim**.  
It illustrates the concept of modular circuit construction and verifies that higher-level logic can be achieved using basic gates.

---

## 📚 References
- [FOSSEE eSim Official Website](https://esim.fossee.in/)  
- [NgSpice Simulation Tool](http://ngspice.sourceforge.net/)

---

