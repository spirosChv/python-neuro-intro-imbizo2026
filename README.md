# Introduction to Python: A Computational Neuroscience Approach

**Author:** Spiros Chavlis  
**Format:** Jupyter Notebooks (`.ipynb`)

## 🧠 Philosophy
This tutorial offers a **functional approach** to learning Python. Instead of memorizing syntax facts in isolation, we introduce programming concepts strictly when they are needed to solve a specific biological problem.

We answer the question: *"Why do I need to learn this?"* by linking every line of code to the physics of a neuron.

## 📂 Curriculum

### Part 1: The Single Neuron
**Goal:** Simulate the Leaky Integrate-and-Fire (LIF) model.
* **Biology:** Membrane potential, Resistance, Capacitance.
* **Python:** Variables, Basic Math, Euler Integration Loop, Plotting.

### Part 2: Synaptic Transmission
**Goal:** Simulate chemical signaling between neurons.
* **Biology:** Conductance-based synapses, Excitatory (EPSP) vs. Inhibitory (IPSP) potentials.
* **Python:** Arrays (NumPy), Time-varying inputs, Logic (`if/else`).

### Part 3: Networks & Noise
**Goal:** Connect two neurons and introduce biological randomness.
* **Biology:** Neural circuits, Signal transfer, Noise.
* **Python:** Writing Functions (`def`), Gaussian Noise (`np.random`), Multi-trace plotting.

### Part 4: The Art of Debugging
**Goal:** Learn to identify and fix errors.
* **Skill:** Reading Tracebacks (NameError, SyntaxError, TypeError).
* **Challenge:** The "Broken Code" exercise—fixing a buggy simulation.

## 🚀 Getting Started

### Prerequisites
You need Python installed (preferably via Anaconda).

### Installation
1.  Clone this repository:
    ```bash
    git clone [https://github.com/your-username/python-neuro-intro-imbizo2026.git](https://github.com/your-username/python-neuro-intro-imbizo2026.git)
    cd python-neuro-intro-imbizo2026
    ```

2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3.  Launch the tutorial:
    ```bash
    jupyter notebook
    ```

## 📚 Resources
* **NumPy:** [numpy.org](https://numpy.org/)
* **Matplotlib:** [matplotlib.org](https://matplotlib.org/)

---
*Created for the Computational Neuroscience community.*
