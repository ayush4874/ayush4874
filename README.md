### Hi, I'm Ayush 

I am a **Final Year B.Tech Computer Science** student at **Jaypee Institute of Information Technology, Noida**.
I specialize in **Compiler Engineering**, **High-Performance Computing (HPC)**, and **Scientific Software Architecture**.

####  **Open Source Engineering**

I contribute to the C++ cores of industry-standard scientific frameworks:

* **[Clad (Cern)](https://github.com/clad-project/clad) (Auto-Differentiation Compiler):**
    * **Focus:** Compiler Plugins & Symbolic Math.
    * **Win:** Implemented symbolic derivatives for C++17 Elliptic Integrals (`std::comp_ellint_1`) in `BuiltinDerivatives.h`, enabling exact gradients over slow numerical fallbacks (PR #1674).
    * **Systems:** Reverse-engineered CMake build scripts to patch shell expansion failures for local builds.

* **[SU2 Foundation](https://github.com/su2code/SU2) (CFD Solver):**
    * **Architecture:** Prototyping **Dynamic Weight Injection** (`MLPCpp` refactoring) to enable real-time Neural Network updates during MPI-parallel simulations.
    * **Contribution:** Author of the **Hybrid PyTorch-SU2 Coupling** workflow.
    * **PRs:** Implemented the "Read-Only" Physics-ML tutorial and documentation (PRs #71, #189).

* **[Brian2 Simulator](https://github.com/brian-team/brian2) (Spiking NNs):**
    * **Optimization:** Implemented compilation overrides to decouple synapse generation from the global build target.
    * **Impact:** Reduced interactive development latency by **~99% (20s → <1s)** for Windows/MSVC users (PR #1744).

####  **Research & Prototypes**
* **Math:** Implemented analytical pullbacks for Elliptic Integrals: $\frac{dK}{dk} = \frac{E(k) - (1-k^2)K(k)}{k(1-k^2)}$.
* **Research:** Author of *"Dynamic Memory Graph Modeling with Quantum Feature Encoding"* (Accepted at ICAICS 2025).
* **Startup:** Building a Stealth AI/ML MVP (Full Stack).

####  **Technical Stack**
* **Compiler & Core:** C++17 (STL, Templates), CMake, Ninja, LLVM/Clang Logic.
* **Scientific:** PyTorch, Clad (Auto-Diff), MPI, NumPy.
* **DevOps:** Docker, GitHub Actions, Linux/WSL.

####  **Education**
* **B.Tech in Computer Science & Engineering** (2022 - 2026)
    * *Jaypee Institute of Information Technology, Noida*

####  **Philosophy**
I believe in "Brutally Honest" engineering: whether it's patching a CMake build or deriving a C++17 math formula, I fix the root cause, not just the symptom.
