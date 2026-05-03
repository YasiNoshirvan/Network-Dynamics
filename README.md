# Network Dynamics and Learning — Course Projects

This repository contains three course projects developed for the **Network Dynamics and Learning** course.

The projects combine theoretical network analysis, numerical simulations, stochastic processes, optimization, and game-theoretic dynamics.  
Each project folder includes the original homework statement, the final report, and the corresponding Jupyter Notebook implementation.

---

## 📌 Repository Overview

The course projects cover different aspects of network dynamics:

- Flow networks and capacity optimization
- Centrality measures in graphs
- Traffic assignment and congestion games
- Continuous-time random walks
- French-DeGroot opinion dynamics
- Multi-particle stochastic systems
- Open queueing networks
- Epidemic spreading on networks
- Vaccination and pandemic simulation
- Network games and best-response dynamics

---

## 🧪 Projects

| Project | Main Focus | Methods / Concepts |
|---|---|---|
| **Project 1** | Network flows, centrality, and traffic optimization | Max-flow/min-cut, Katz centrality, PageRank, Wardrop equilibrium, social optimum, toll design |
| **Project 2** | Random walks, opinion dynamics, and open networks | Continuous-time Markov chains, return/hitting times, French-DeGroot dynamics, consensus, Gillespie simulation |
| **Project 3** | Epidemic spreading and network games | SIR/SIRV models, preferential attachment, vaccination, H1N1 parameter estimation, Nash equilibria, best-response dynamics |

---

## 🔹 Project 1 — Network Flows, Centrality, and Traffic Optimization

The first project focuses on three network analysis problems.

The first part studies a flow network using the **Max-Flow Min-Cut Theorem** and investigates how additional capacity can be allocated to increase throughput from a source node to a destination node.

The second part analyzes node importance using **Katz centrality** and **PageRank**, with a focus on how different centrality measures can assign different importance to bridge nodes and local hubs.

The third part applies network optimization to a simplified **Los Angeles highway network**, including shortest path computation, maximum flow, Wardrop equilibrium, social optimum, toll design, and Price of Anarchy analysis.

---

## 🔹 Project 2 — Continuous-Time Random Walks, DeGroot Dynamics, and Open Networks

The second project studies stochastic processes and opinion dynamics on networks.

It starts with a **continuous-time random walk** on a closed network and compares simulated return and hitting times with theoretical values.  
It then analyzes **French-DeGroot opinion dynamics**, studying when opinions converge to consensus and how graph structure affects asymptotic behavior.

The project also extends the analysis to **multi-particle dynamics** and an **open network** with external arrivals, comparing proportional-rate and fixed-rate forwarding mechanisms and their stability properties.

---

## 🔹 Project 3 — Epidemic Spreading, Vaccination, and Network Games

The third project focuses on epidemic dynamics and game-theoretic processes on networks.

The first part simulates the spread of an epidemic using the **SIR model** on both regular and preferential attachment networks.  
The model is extended to include vaccination through an **SIRV model**, and then calibrated against real H1N1 pandemic data from Sweden using RMSE-based parameter estimation.

The second part studies **network games** with coordination and anti-coordination players. It computes pure Nash equilibria, analyzes asynchronous best-response dynamics as a Markov chain, and studies noisy best-response behavior in the vanishing-noise limit.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- SciPy
- NetworkX
- Matplotlib
- CVXPY
- Stochastic simulation
- Graph algorithms
- Network optimization

---

## 📚 Course Information

**Course:** Network Dynamics and Learning  
**Program:** M.Sc. Data Science and Engineering  
**Institution:** Politecnico di Torino  
**Type:** Homework projects / numerical assignments

---

## ⚠️ Note

These projects were developed for academic purposes.  
Each report is included together with the corresponding code and original assignment statement.

---

## 📬 Contact

**Yasaman Noshirvanbaboli**  
GitHub: [YasiNoshirvan](https://github.com/YasiNoshirvan)
