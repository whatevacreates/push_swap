# 🧮 Push_Swap

### 🎯 Project Overview  
Push_Swap is a **sorting algorithm challenge** that tests mastery of **data structures**, **algorithmic optimisation**, and **constrained operations**.  
The goal: sort a stack of integers using only a limited set of moves and an auxiliary stack.  
It’s a deep dive into efficiency — both in computational logic and mental clarity.

---

## ✅ My Approach  
I built a **multi-strategy sorting system** that adapts dynamically to the input size:

🔹 **Small stacks (≤ 5):** direct minimal-move sorting  
🔹 **Medium & large stacks:** adaptive cost-based algorithm analysing the cheapest sequence of rotations and pushes  
🔹 **Input normalisation:** coordinate compression for consistent index mapping  
🔹 **Precision execution:** no random shuffling — every move is intentional and optimised  

🧭 Additionally, I implemented a **unique time-management logic**, adjusting internal operation delays and pacing dynamically — turning the whole process into a kind of *rhythmic algorithmic choreography.*

---

## 🍀 Bonus: Custom Tester  
As a personal challenge, I created a **custom testing suite** that automatically:

- Generates random stacks of varying sizes  
- Compares move counts with target thresholds  
- Validates output correctness (`OK` / `KO`) and measures efficiency  
- Logs results with **color-coded performance metrics**

🏅 This bonus earned me a **distinction grade of 125%** for the project at *42 Lausanne.*

---

## ⚙️ Usage  

```bash
make
./push_swap <list_of_integers>
