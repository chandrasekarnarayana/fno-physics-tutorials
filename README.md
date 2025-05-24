# 📘 Mastering Fourier Neural Operators (FNO) with Physics-Based Examples

Welcome to **fno-physics-tutorials** — a curated collection of Jupyter notebooks designed to help you master **Fourier Neural Operators (FNO)** through progressive, hands-on, and physics-inspired learning.

FNOs are a cutting-edge deep learning architecture capable of learning mappings between infinite-dimensional function spaces, making them ideal for solving partial differential equations (PDEs) efficiently and with high generalization.

---

## 🔍 Overview of Notebooks

| Notebook | Title | Description |
|----------|-------|-------------|
| `01_FFT_and_HeatEquation.ipynb` | **Fourier Transform & Heat Equation** | Learn FFT basics, visualize signal decomposition, and solve the 1D heat equation using spectral methods. |
| `02_Intro_to_FNO.ipynb` | **Introduction to FNO** | Understand the theory and architecture of FNOs. Build a minimal 1D FNO model to solve a PDE. |
| `03_FNO_2D_DarcyFlow.ipynb` | **Darcy Flow Simulation** | Apply FNOs to model 2D fluid flow through porous media using benchmark Darcy Flow data. |
| `04_Physics_Inverse_Problems_FNO.ipynb` | **Inverse Physics Problems** | Use FNOs to estimate PDE parameters and solve inverse problems in physical systems. |
| `05_Advanced_FNO_Hybrid.ipynb` | **Hybrid and Advanced Models** | Combine FNO with PINNs, add noise robustness, and solve wave/transport equations. |

---

## 🚀 Why Learn FNO?

- Mesh-independent operator learning
- Generalizes across initial conditions and domains
- Outperforms CNNs and RNNs on PDE tasks
- Applicable in physics, climate modeling, mechanics, and bioimaging

---

## 📦 Installation

Clone the repository and install required dependencies:

```bash
git clone https://github.com/yourusername/fno-physics-tutorials.git
cd fno-physics-tutorials
pip install -r requirements.txt
````

**Dependencies include:**
`numpy`, `matplotlib`, `scipy`, `torch`, `torchvision`, `einops`, `torch-fft`
(Optional: `jax`, `pytorch-lightning`, `kornia` for speed & augmentation)

---

## 📂 Datasets

* **Darcy Flow Dataset:**
  Download from [Fourier Neural Operator GitHub](https://github.com/zongyi-li/fourier_neural_operator#darcy-flow)

* Synthetic datasets are generated directly in the notebooks where required.

---

## 🧠 Learning Outcomes

* Understand the core math: Fourier transforms and operator theory
* Build and train FNOs from scratch using PyTorch
* Apply FNOs to real-world PDE problems
* Integrate FNOs with hybrid methods (e.g. PINNs)
* Visualize and interpret spectral learning behavior

---

## 🌐 Share and Connect

Share your learnings or variations on:

* **X/Twitter:** `@ChandrasekarSN3 and #FNO4Physics`
* **LinkedIn:** Tag `https://www.linkedin.com/in/snchandrasekar/` and `#AI4Science`
* **Pull Requests:** Contributions welcome!
