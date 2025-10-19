<div align="center">

# Hey, I'm Zihan Zhang 👋

<img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=500&size=22&duration=3000&pause=800&color=6366F1&center=true&vCenter=true&width=600&lines=Ph.D.+Candidate+in+ECE;NVM+Device+Modeling+%26+System+Co-Design;AI+Hardware+Acceleration+Researcher;Physics-Informed+ML+%26+Generative+Models" alt="Typing SVG" />

<p>
  <a href="mailto:zihan.zhang@tufts.edu">
    <img src="https://img.shields.io/badge/Email-zihan.zhang@tufts.edu-6366F1?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://linkedin.com/in/zihanz">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/shadyn3mo">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

📍 Somerville, MA

<img src="https://komarev.com/ghpvc/?username=shadyn3mo&label=Visitors&color=6366F1&style=flat-square" alt="Profile views" />

</div>

---

## 🌟 About Me

I'm a Ph.D. Candidate in Electrical and Computer Engineering at **Tufts University**, where my doctoral research spans emerging non-volatile memories (NVM), AI/ML hardware acceleration, and advanced device modeling. I bridge device-level physics to system-level PPA (Performance/Power/Area) and reliability decisions using physics-informed neural networks (PINNs) and generative models (CVAEs).

**My Research Focus:**
- 🔬 **Non-Volatile Memory (NVM)**: ReRAM/FeFET device modeling and optimization
- 🚀 **AI Hardware Acceleration**: Designing efficient architectures for edge computing and XR systems
- 🧠 **Physics-Informed ML**: Combining PDEs with deep learning for rapid, accurate device simulation
- ⚡ **System Co-Design**: Automated technology-application co-design frameworks

**Recent Highlight:**
My first-author work on the **PIGen framework** (ICCAD 2025) achieved up to **93x speedup** over traditional SPICE simulations while maintaining over **96% accuracy** in key switching dynamics, enabling rapid and robust co-design exploration even from sparse data.

**Education:**
- 🎓 **Ph.D. in ECE** | Tufts University (2021 - Present)
- 🎓 **M.S. in Computer Engineering** | University of Delaware (3.97/4.0 GPA)

## 🛠️ Technical Skills

<table>
<tr>
  <td valign="top" width="33%">

### Modeling & EDA
- **TCAD**: Synopsys Sentaurus
- **Circuit Sim**: Cadence Virtuoso/Spectre (SPICE)
- **Memory Sim**: NVSim
- **Multiphysics**: COMSOL
- **Version Control**: Git

  </td>
  <td valign="top" width="33%">

### Programming & ML
<div align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,cpp,matlab&perline=2" />
</div>

- Python (PyTorch, NumPy, SciPy)
- C++ / Verilog-A
- MATLAB
- Machine Learning (PINNs, DNNs, CVAEs)

  </td>
  <td valign="top" width="33%">

### Research Domains
- Semiconductor Device Physics
- Non-Volatile Memory (ReRAM/FeFET)
- eDRAM Technology
- AI Hardware Acceleration
- Generative Models
- PPA & Reliability Analysis

  </td>
</tr>
</table>

## 📊 GitHub Activity

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=shadyn3mo&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117" alt="GitHub Stats"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shadyn3mo&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top Languages"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shadyn3mo&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak" />
</div>

## 🔬 Featured Research Projects

### PIGen: Generative Physics-Informed Co-Design for ReRAM
**ICCAD 2025 | First Author**

A novel PDE-constrained PINN + CVAE workflow that bridges device physics to system-level metrics for automated technology-application co-design.

**Key Achievements:**
- ⚡ **93x computational speedup** over SPICE for switching dynamics inference (7.1 ms vs. 664 ms)
- 🎯 **>96% accuracy** in switching dynamics under sparse data conditions (~9% of training set)
- 🔄 Enabled rapid design-space exploration with PINN-driven endurance landscapes
- 📊 Matched SPICE results while exposing reliability vs. PPA trade-offs

**Technologies:** Physics-Informed Neural Networks (PINN), Conditional Variational Autoencoders (CVAE), PyTorch, ReRAM Device Modeling

---

### MemSysExplorer (MSX): Next-Generation Memory Systems
**NSF CIRC Funded Program | Collaborative Research**

Community tools and interfaces for exploring and evaluating next-generation memory systems with focus on NVM and eDRAM technologies.

#### msxFI: A Memory Fault Injection Framework for Deep Learning Reliability

Designed and developed **msxFI**, a Python-based framework to evaluate the resilience of deep learning models against physical memory failures—my primary contribution to the MemSysExplorer project.

**Key Contributions:**
- 🏗️ **Extensible Fault Model Architecture**: Implemented physically-grounded fault models for diverse memory technologies:
  - Non-Volatile Memories (RRAM, FeFET) with Multi-Level Cell (MLC) support
  - DRAM/eDRAM with operating-condition-aware models (temperature, refresh rate, voltage)

- 🔗 **PyTorch Integration**: Engineered seamless integration with PyTorch to inject faults directly into neural network parameters, enabling end-to-end evaluation of application-level accuracy degradation

- 📊 **Quantization Format Support**: Integrated extensive support for various data quantization formats and their corresponding bit-level mappings to memory cells:
  - FP32/FP16, bfloat16
  - Fixed-point representations
  - AdaptivFloat format

- 🔍 **Design-Space Exploration Tool**: Developed automated parameter sweep capabilities to identify DRAM operating parameters that achieve user-defined target fault rates, facilitating reliability analysis

- 🛠️ **Simulator Enhancement**: Enhanced NVSim simulator with NVM and 1T1C/3T1C eDRAM models for <16nm nodes to broaden system-level power and performance analysis

**Technologies:** Python, PyTorch, NVSim, Memory Architecture Simulation, Fault Injection, DNN Reliability Analysis, Quantization Formats

## 📝 Publications

**PIGen: Accelerating Re-RAM Co-Design via Generative Physics-Informed Modeling**
*Zihan Zhang and Marco Donato*
**IEEE/ACM International Conference on Computer-Aided Design (ICCAD)**, October 2025

---

## 🏆 Awards & Recognition

🌟 **Featured Student, School of Engineering Brochure**
*Tufts University* | November 2024
Selected as a featured student highlighting academic excellence and research contributions

🥈 **Second Place, ECE Poster Competition**
*Tufts University, ECE Department* | October 2023
Awarded for research and presentation of **nvmXR**: a novel design space exploration framework for optimizing hybrid NVM and Processing-In-Memory (PIM) architectures for energy-efficient Edge-XR systems

---

## 🎤 Presentations

- **Work-in-Progress Presenter** | 61st & 62nd Design Automation Conference (DAC)
  📍 San Francisco, CA | June 2024 & June 2025

- **Presenter** | 14th Non-Volatile Memories Workshop (NVMW)
  📍 San Diego, CA | March 2023

---

## 💡 Research Philosophy

> *"The best device models don't just simulate reality—they illuminate the physics and accelerate innovation."*

I believe in bridging the gap between fundamental device physics and practical system design. By combining physics-informed machine learning with generative models, we can accelerate the design cycle while maintaining physical accuracy and enabling robust co-design exploration.

---

<div align="center">

### Let's Collaborate

I'm always interested in discussing emerging memory technologies, AI hardware acceleration, or collaborative research opportunities. Feel free to reach out!

**Thanks for visiting!**

</div>
