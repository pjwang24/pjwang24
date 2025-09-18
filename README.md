<!-- Animated Wave Header with Circuit Pattern -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,5,10&height=180&section=header&text=Peter%20Wang&fontSize=80&fontAlignY=35&animation=twinkling&desc=Hardware%20Architect%20•%20UC%20Berkeley%20EECS&descAlignY=55&descSize=22" alt="header"/>
</div>

<!-- Typing Animation with Hardware Focus -->
<div align="center">
  
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00FF41&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=100&lines=ARM%20SoC%20Architecture%20Engineer%20⚡;RISC-V%20ASIC%20Designer%20🔧;AWS%20Trainium%20Researcher%20🚀;Building%20Next-Gen%20Silicon%20💾)](https://git.io/typing-svg)

</div>

<!-- Professional Badges -->
<div align="center">
  
  [![Profile Views](https://komarev.com/ghpvc/?username=pjwang24&label=Profile%20Views&color=brightgreen&style=for-the-badge)](https://github.com/pjwang24)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/peterwang-eecs)
  [![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pjwang2324@berkeley.edu)
  [![Portfolio](https://img.shields.io/badge/Portfolio-Visit-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://pjwang24.github.io/)
  
</div>

<br>

<!-- Circuit Animation -->
<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">
</div>

## 🔬 About Me

<img align="right" alt="Coding" width="400" src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif">

```verilog
module PeterWang (
    input  wire clk,
    input  wire reset_n,
    output reg  [31:0] innovation
);

  parameter ROLE = "CS @ Berkeley | EE Minor";
  parameter GPA = 3.57;
  parameter FOCUS = "SoC Architecture & ASIC Design";
  
  reg [2:0] current_project;
  localparam ARM_NEOVERSE = 3'b001;
  localparam AWS_TRAINIUM = 3'b010;
  localparam RISCV_ASIC  = 3'b100;
  
  always @(posedge clk) begin
    if (!reset_n) 
      innovation <= 32'h0;
    else
      innovation <= innovation + 32'h1337;
  end
endmodule
```

### 🎯 Current Focus @ ARM & Berkeley SLICE Lab
- 🏗️ **ARM Neoverse CSS:** Pin analysis & AMBA protocol mapping for 20M+ pins
- 🧠 **AWS Trainium:** 2D systolic array design for Zebra accelerator
- 🔌 **RISC-V ASIC:** Full RTL-to-GDS flow with SKY130 PDK
- ⚡ **Performance:** 85% RAM reduction in SoC-scale analysis

<br clear="both">

---

## 🛠️ Technical Stack

<div align="center">

### 🔧 Hardware Design & Verification
![Verilog](https://img.shields.io/badge/Verilog-Circuit_Design-00838F?style=for-the-badge&logo=v&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-Verification-1E88E5?style=for-the-badge&logo=v&logoColor=white)
![VHDL](https://img.shields.io/badge/VHDL-FPGA-9C27B0?style=for-the-badge&logo=xilinx&logoColor=white)

### 🖥️ EDA Tools & PDKs
![Synopsys](https://img.shields.io/badge/Synopsys_DC-Synthesis-5E35B1?style=for-the-badge)
![Cadence](https://img.shields.io/badge/Cadence_Genus-PnR-0288D1?style=for-the-badge)
![VCS](https://img.shields.io/badge/VCS-Simulation-00695C?style=for-the-badge)
![Innovus](https://img.shields.io/badge/Innovus-Physical_Design-F57C00?style=for-the-badge)
![ModelSim](https://img.shields.io/badge/ModelSim-Verification-8BC34A?style=for-the-badge)
![Vivado](https://img.shields.io/badge/Vivado-FPGA-FF6F00?style=for-the-badge)
![OpenROAD](https://img.shields.io/badge/OpenROAD-Open_Source-4CAF50?style=for-the-badge)
![SKY130](https://img.shields.io/badge/SKY130_PDK-ASIC-795548?style=for-the-badge)

### ⚡ High-Performance Computing
![CUDA](https://img.shields.io/badge/CUDA-GPU_Programming-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![C++](https://img.shields.io/badge/C++-System_Programming-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-ML_&_Automation-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-Backend-00ADD8?style=for-the-badge&logo=go&logoColor=white)

### 🤖 ML/AI Frameworks
![PyTorch](https://img.shields.io/badge/PyTorch-Deep_Learning-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-Data_Processing-FFD43B?style=for-the-badge)
![CUDA Kernels](https://img.shields.io/badge/CUDA_Kernels-36%25_Faster-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

</div>

---

## 💼 Professional Experience

<div align="center">

### 🏢 **ARM** | Solutions Engineering, SoC Architecture Intern
*May 2025 — Aug 2025*

```mermaid
graph LR
    A[20M+ Pins] -->|Polars Pipeline| B[Protocol Classification]
    B -->|AMBA Analysis| C[CHI/AXI/APB]
    C -->|85% RAM Cut| D[SoC-Scale Analysis]
    
    style A fill:#1a1a1a,stroke:#00ff41,color:#00ff41
    style B fill:#1a1a1a,stroke:#00ff41,color:#00ff41
    style C fill:#1a1a1a,stroke:#00ff41,color:#00ff41
    style D fill:#1a1a1a,stroke:#00ff41,color:#00ff41
```

### 🔬 **Berkeley SLICE Lab** | AWS Trainium Architecture Researcher
*Jun 2025 — May 2026 | $500K+ Research Grant*

- Designing flexible 2D systolic arrays for Zebra accelerator
- Building PyTorch-to-Trainium framework via TeAAL
- Implementing profile-guided optimization for AWS infrastructure

### 📚 **UC Berkeley** | First EECS Peer Advisor
*Sep 2024 — May 2025 | Supporting 1,000+ Students*

</div>

---

## 🚀 Featured Hardware Projects

<div align="center">
  
| 🎯 Project | 📝 Description | 🛠️ Tech Stack | 📊 Impact | 🔗 Links |
|-----------|---------------|--------------|----------|---------|
| **3-Stage RISC-V ASIC** | Full RTL-to-GDS pipelined CPU with hazard resolution | ![Verilog](https://img.shields.io/badge/-Verilog-00838F?style=flat) ![SKY130](https://img.shields.io/badge/-SKY130-795548?style=flat) | Optimized timing, area, power | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat&logo=github)](https://github.com/pjwang24) |
| **AWS Trainium Kernel** | NKI-optimized inference with manual memory scheduling | ![CUDA](https://img.shields.io/badge/-NKI-FF9900?style=flat) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat) | Low-latency execution | [![Docs](https://img.shields.io/badge/Docs-FF9900?style=flat&logo=amazon)](https://github.com/pjwang24) |
| **Branch Predictor** | Perceptron predictor with weighted history | ![C++](https://img.shields.io/badge/-C++-00599C?style=flat) | 13% misprediction reduction | [![Results](https://img.shields.io/badge/Results-4CAF50?style=flat)](https://github.com/pjwang24) |
| **Finger-Vein Recognition** | IEEE Published NASNet biometric system | ![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat) | 36% training speedup | [![IEEE](https://img.shields.io/badge/IEEE-Paper-00629B?style=flat&logo=ieee)](https://ieeexplore.ieee.org/abstract/document/9650980) |
| **EV Optimization** | Honda Research: ML-powered routing with L2 Ridge | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat) ![K--means](https://img.shields.io/badge/-KMeans-F7931E?style=flat) | 100K+ sessions analyzed | [![PDF](https://img.shields.io/badge/PDF-Research-DC382D?style=flat&logo=adobe)](https://drive.google.com/file/d/1eJ1-RvuOJprvE-OXcbFbRktth9Zmozam/view) |

</div>

<div align="center">
  <a href="https://github.com/pjwang24?tab=repositories">
    <img src="https://img.shields.io/badge/🔍_View_All_Hardware_Projects-100000?style=for-the-badge&logo=github&logoColor=white&labelColor=00838F&color=00ACC1" alt="View Projects">
  </a>
</div>

---

## 📊 GitHub Analytics

<div align="center">
  <img width="49%" height="195px" src="https://github-readme-stats.vercel.app/api?username=pjwang24&show_icons=true&count_private=true&hide_border=true&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9&bg_color=0d1117" alt="GitHub Stats" /> 
  <img width="49%" height="195px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pjwang24&layout=compact&hide_border=true&title_color=00ff41&text_color=c9d1d9&bg_color=0d1117&langs_count=8" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=pjwang24&theme=black-ice&hide_border=true&stroke=00ff41&background=0D1117&ring=00ff41&fire=00ff41&currStreakLabel=00ff41" alt="GitHub Streak" />
</div>

---

## 🏆 Achievements & Recognition

<div align="center">

### 🎖️ Awards & Honors
![Award](https://img.shields.io/badge/Jim_&_Donna_Gray_Award-$10,000-FFD700?style=for-the-badge)
![Scholar](https://img.shields.io/badge/Leadership_Scholar-$2,000-C0C0C0?style=for-the-badge)
![IEEE](https://img.shields.io/badge/IEEE_Member-Active-00629B?style=for-the-badge&logo=ieee&logoColor=white)

### 📚 Publications
[![IEEE ISPACS 2021](https://img.shields.io/badge/IEEE_ISPACS_2021-Finger--Vein_Recognition_with_NASNet-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org/abstract/document/9650980)

</div>

---

## 🎯 2025-2026 Roadmap

<div align="center">

```mermaid
timeline
    title Hardware Development Timeline
    
    Q1 2025 : ARM Neoverse Project
            : AMBA Protocol Mastery
            
    Q2 2025 : Trainium Architecture
            : TeAAL Framework Development
            
    Q3 2025 : RISC-V Tape-out
            : Research Publication
            
    Q4 2025 : Open Source Contributions
            : Graduate Applications
            
    2026    : Industry Position
            : Advanced Architecture Research
```

</div>

### 🔬 Current Research Interests
- **🧠 Neuromorphic Computing** - Event-driven architectures
- **🔐 Hardware Security** - Side-channel attack mitigation
- **📐 Domain-Specific Architectures** - ML accelerators & systolic arrays
- **⚡ Near-Data Processing** - Compute-in-memory designs

---

## 🤝 Let's Connect!

<div align="center">
  
**Open to discussing SoC architecture, ASIC design, and hardware acceleration opportunities!**

<a href="mailto:pjwang2324@berkeley.edu">
  <img src="https://img.shields.io/badge/Email-pjwang2324@berkeley.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>
<a href="https://linkedin.com/in/peterwang-eecs">
  <img src="https://img.shields.io/badge/LinkedIn-peterwang--eecs-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="tel:909-551-5416">
  <img src="https://img.shields.io/badge/Phone-(909)_551--5416-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Phone">
</a>
<a href="https://github.com/pjwang24">
  <img src="https://img.shields.io/badge/GitHub-pjwang24-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>

### 💡 Quick Facts
<details>
<summary><b>⚡ Click for Hardware Achievements</b></summary>
<br>

> 🔧 **ASIC Design:** Completed full RTL-to-GDS flow with SKY130 PDK
> 
> 📊 **Scale:** Analyzed 20M+ pins for ARM SoC architecture
> 
> 🚀 **Optimization:** Achieved 85% RAM reduction in protocol analysis
> 
> 🎯 **Performance:** Reduced branch misprediction by ~13%
> 
> ⚡ **CUDA:** 36% training time reduction with custom kernels

</details>

</div>

---

## 📈 Contribution Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=pjwang24&custom_title=Hardware%20Development%20Activity&bg_color=0d1117&color=00ff41&line=00ff41&point=00ff41&area_color=1a1a1a&title_color=ffffff&area=true&hide_border=true" alt="Contribution Graph" />
</div>

---

<div align="center">
  
### 🐍 Contribution Snake
  
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/pjwang24/pjwang24/blob/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/pjwang24/pjwang24/blob/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://github.com/pjwang24/pjwang24/blob/output/github-contribution-grid-snake.svg">
</picture>

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,5,10&height=100&section=footer&animation=twinkling" width="100%" alt="footer">
</div>

<div align="center">
  
**"The best hardware is the one that makes software developers happy."** - Linus Torvalds

Building the silicon that powers tomorrow 🔧

</div>
