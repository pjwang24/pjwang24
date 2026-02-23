<h1 align="center">Peter Wang</h1>
<p align="center">
  SoC Architecture · ML Accelerators · ASIC Design<br>
  B.S. Computer Science & EE Minor · UC Berkeley '26
</p>

<p align="center">
  <a href="mailto:pjwang2324@berkeley.edu">Email</a> &nbsp;&middot;&nbsp;
  <a href="https://www.linkedin.com/in/peterwang-eecs/">LinkedIn</a> &nbsp;&middot;&nbsp;
  <a href="https://pjwang24.github.io/">Portfolio</a> &nbsp;&middot;&nbsp;
  <a href="https://pjwang24.github.io/Peter%20Wang%20Resume.pdf">Resume</a>
</p>

---

### Currently

| | |
|---|---|
| **SoC Architecture Intern** · Arm Neoverse CSS | Protocol intelligence infrastructure for Arm Compute Subsystems. Polars pipeline classifying 20M+ AMBA pins with 85% RAM reduction. |
| **ML Accelerator Researcher** · UC Berkeley SLICE Lab | AWS-funded research designing Zebra, a flexible 2D systolic array for dense/sparse tensor workloads. |

---

### Featured Projects

<details open>
<summary><strong>Bare-Metal MNIST on Custom RISC-V + INT8 Matmul Accelerator</strong> &nbsp; <code>SystemVerilog · Sky130 · Verilator · OpenLane</code></summary>
<br>

End-to-end inference on a custom RV32IM core with a decoupled 4x4 INT8 outer-product matmul engine. 100/100 MNIST accuracy across a 2-layer MLP, verified in cycle-accurate simulation and pushed through a Sky130 OpenLane RTL-to-GDS flow.

| Cycles/Image | Speedup | Die Area | Accuracy |
|:---:|:---:|:---:|:---:|
| ~20K | **24.45x** | 1.44 mm² | 100% |

</details>

<details open>
<summary><strong>3-Stage Pipelined RISC-V CPU & Cache</strong> &nbsp; <code>Verilog · Sky130 PDK</code></summary>
<br>

RV32I core with GShare branch predictor and 2-way set-associative write-back cache. Parallel ALU architecture with a 5-entry fetch-decode FIFO.

| CPI | Cache Speedup | Pipeline Stages |
|:---:|:---:|:---:|
| **1.05** | 40%+ | 3 |

</details>

<details>
<summary><strong>PackBits RLE Decompression Accelerator Tapeout</strong> &nbsp; <code>Chisel · TSMC 16nm · Expected Spring 2026</code></summary>
<br>

Hardware accelerator for lossless PackBits decompression with a custom RISC-V instruction interface. Full RTL-to-GDS on TSMC 16nm.

</details>

<details>
<summary><strong>Sparse Tensor Accelerator Modeling</strong> &nbsp; <code>TeAAL · Python</code></summary>
<br>

Modeled the Trapezoid accelerator — 2D spatial array with multi-fiber intersection units. Evaluated Gustavson vs inner-product dataflows for PE utilization.

</details>

<details>
<summary><strong>AWS Trainium Kernel Optimization</strong> &nbsp; <code>Neuron Kernel Interface · Python</code></summary>
<br>

Extending TeAAL for inference kernels with engine-aware compute mapping and manual memory scheduling on AWS Trainium.

</details>

---

### Technical Stack

| Domain | Tools |
|---|---|
| **EDA & Hardware** | Synopsys DC, Cadence Genus/Innovus, VCS, ModelSim, Vivado, OpenROAD/Yosys, gem5, Sky130 |
| **Languages** | Verilog, SystemVerilog, Python, C/C++, CUDA, Chisel, Java, SQL, MATLAB |
| **ML & Data** | PyTorch, ONNX Runtime, Polars, NumPy, Pandas, SciPy, scikit-learn |

---

### Stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=pjwang24&theme=dark&hide_border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=pjwang24&theme=default&hide_border=true" />
    <img alt="GitHub Streak" src="https://streak-stats.demolab.com/?user=pjwang24&theme=default&hide_border=true" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=pjwang24&layout=compact&theme=dark&hide_border=true&langs_count=8" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=pjwang24&layout=compact&theme=default&hide_border=true&langs_count=8" />
    <img alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pjwang24&layout=compact&theme=default&hide_border=true&langs_count=8" />
  </picture>
</p>

---

### Publication

**Finger-Vein Recognition using a NASNet with a Cutout** · ISPACS 2021 · IEEE — [Read Paper](https://ieeexplore.ieee.org/abstract/document/9650980)

---

<p align="center">
  <sub>Available for SoC architecture, ML accelerator, or ASIC design roles starting June 2026.</sub>
</p>
