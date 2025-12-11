### Hi, I'm Ayush 

I am a **Final Year B.Tech Computer Science** student at **Jaypee Institute of Information Technology, Noida**.
I specialize in **Physics-ML Systems**, **HPC**, and **Scientific Software Architecture**.

####  **Open Source Engineering**
I act as a bridge between Deep Learning frameworks and C++ Scientific Solvers:

* **[SU2 Foundation](https://github.com/su2code/SU2) (CFD Solver):**
    * *Architecture:* Prototyping **Dynamic Weight Injection** (`MLPCpp` refactoring) to enable real-time Neural Network updates during MPI-parallel simulations.
    * *Contribution:* Author of the **Hybrid PyTorch-SU2 Coupling** workflow.
    * *PRs:* Implemented the "Read-Only" Physics-ML tutorial and documentation (PRs #71, #189).
* **[Brian2 Simulator](https://github.com/brian-team/brian2) (Spiking NNs):**
    * *Optimization:* Implemented compilation overrides to decouple synapse generation from the global build target.
    * *Impact:* Reduced interactive development latency by **~99% (20s → <1s)** for Windows/MSVC users (PR #1744).

####  **Research & Prototypes**
* **Physics-ML:** Built `train_online.py`, a script coupling SU2 (via `pysu2`) with PyTorch to extract flow physics (RMS Density) for online training loops.
* **Research:** Author of *"Dynamic Memory Graph Modeling with Quantum Feature Encoding"* (Accepted at ICAICS 2025).
* **Startup:** Building a Stealth AI/ML MVP (Full Stack).

####  **Technical Stack**
* **HPC Systems:** C++ (MPI, Ninja Build System), CMake, Linux/WSL.
* **Scientific:** PyTorch, SU2 PyWrapper, NumPy, Brian2.
* **DevOps:** Docker, GitHub Actions (CI/CD).

####  **Education**
* **B.Tech in Computer Science & Engineering** (2022 - 2026)
    * *Jaypee Institute of Information Technology, Noida*

####  **Philosophy**
I believe in "Brutally Honest" engineering: breaking encapsulation when necessary (e.g., `CLookUp_ANN.hpp`) to solve real integration bottlenecks.
