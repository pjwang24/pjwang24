<h1 align="center">Peter Wang</h1>
<p align="center">
  <strong>SoC Architecture · ML Accelerators · ASIC Design</strong><br>
  B.S. Computer Science & EE Minor · UC Berkeley · Class of 2026
</p>

<p align="center">
  <a href="mailto:pjwang2324@berkeley.edu">Email</a> · 
  <a href="https://www.linkedin.com/in/peterwang-eecs/">LinkedIn</a> · 
  <a href="https://pjwang24.github.io/">Portfolio</a> · 
  <a href="https://pjwang24.github.io/Peter%20Wang%20Resume.pdf">Resume</a>
</p>

---

### Currently

**SoC Architecture Intern** — Arm, Neoverse CSS Team  
Building protocol intelligence infrastructure for next-gen Arm Compute Subsystems. Developed a Polars-based pipeline classifying 20M+ pins to identify AMBA protocols, achieving 85% RAM reduction. Mapping instance paths to die-level centroids and validating protocol summaries against STA and floorplan intent.

**ML Accelerator Researcher** — UC Berkeley SLICE Lab  
AWS-funded research on hardware-software co-design for AI workloads. Designing Zebra, a flexible 2D systolic array supporting dense and sparse tensor operations. Extending TeAAL for inference kernels via Neuron Kernel Interface with engine-aware compute mapping.

---

### Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>3-Stage Pipelined RISC-V CPU & Cache</h4>
      <sub>Verilog · SKY130 PDK</sub>
      <br><br>
      RV32I pipelined core with GShare branch predictor, 2-way set-associative write-back cache, and parallel ALU architecture. Split critical path into functional units (adder, comparator, shifter) and added a 5-entry FIFO between Fetch and Decode to decouple stalls. Achieved <strong>1.05 CPI</strong> with 40%+ cache speedup.
    </td>
    <td width="50%" valign="top">
      <h4>PackBits RLE Decompression Accelerator</h4>
      <sub>Chisel · TSMC 16nm · Expected Spring 2026</sub>
      <br><br>
      Hardware accelerator for lossless PackBits run-length encoding targeting TIFF/PSD processing. Custom RISC-V instruction interface triggers accelerator from a GP core, streaming compressed data through decompression logic. Full RTL-to-GDS flow on TSMC 16nm via TSMC-sponsored EE 194.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>Sparse Tensor Accelerator Modeling</h4>
      <sub>TeAAL · Python</sub>
      <br><br>
      Modeled the Trapezoid accelerator in TeAAL — a 2D spatial array with multi-fiber intersection units for varying sparsity levels. Evaluated Gustavson-based vs inner-product dataflows, optimizing fiber-tree mappings to maximize PE utilization and minimize off-chip memory traffic.
    </td>
    <td width="50%" valign="top">
      <h4>AWS Trainium Kernel Optimization</h4>
      <sub>Neuron Kernel Interface · Python</sub>
      <br><br>
      Extending TeAAL's modular architecture specifications to optimize inference kernels using NKI with engine-aware compute mapping and manual memory scheduling for AWS Trainium hardware.
    </td>
  </tr>
</table>

---

### Technical Stack

**Hardware & EDA** — Synopsys DC, Cadence Genus/Innovus, VCS, ModelSim, Vivado, OpenROAD/Yosys, gem5, SKY130 PDK  
**Languages** — Verilog, SystemVerilog, Python, C/C++, CUDA, Chisel, Java, SQL, MATLAB  
**ML & Data** — PyTorch, ONNX Runtime, Polars, NumPy, Pandas, SciPy, scikit-learn

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pjwang24&show_icons=true&theme=default&hide_border=true&count_private=true" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pjwang24&layout=compact&theme=default&hide_border=true&langs_count=8" height="165" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=pjwang24&theme=default&hide_border=true" alt="GitHub Streak" />
</p>

---

### Publication

**Finger-Vein Recognition using a NASNet with a Cutout**  
ISPACS 2021 · IEEE — [Read Paper](https://ieeexplore.ieee.org/abstract/document/9650980)

---

<p align="center">
  <sub>Looking for SoC architecture, ML accelerator, or ASIC design roles starting June 2026.</sub>
</p>
