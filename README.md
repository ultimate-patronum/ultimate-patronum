<h3>Hi, I'm Riddhima 👋</h3>

Computer Engineering student at UBC (BASc + Minor in Commerce, expected May 2028) building software for robots, embedded systems, and space tech. I lead the software team on UBC Mars Rover, and I like working close to the hardware: real-time firmware, sensor pipelines, and debugging across the whole stack.

**Things I code with are...**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Verilog / VHDL](https://img.shields.io/badge/Verilog%20%2F%20VHDL-6E4C13?style=for-the-badge)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-6BA43A?style=for-the-badge&logo=freertos&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

<details>
<summary><b>🛠️ More skills & tools</b></summary>
<br>

- **Embedded & RTOS:** FreeRTOS, microcontrollers (RP2040), interrupts, SPI, UART, CAN bus, bare-metal C, real-time systems
- **Robotics:** ROS 2, OpenCV, RGBD/LiDAR perception, PID control, Unity simulation
- **Hardware debug:** oscilloscopes, logic analyzers, ModelSim, SignalTap, Intel DE1-SoC FPGA
- **AI/ML:** RAG pipelines, ChromaDB, embeddings, LLM orchestration, model evaluation
- **Tools:** Git, GitLab CI/CD, Docker, Make, pytest-BDD, Unreal Engine, Blender

</details>

<details>
<summary><b>👩‍💻 More About Me!</b></summary>
<br>

I'm happiest where software meets hardware, whether that's tracing a fault from a scope trace up to ROS 2 behaviour or building simulation pipelines so a team can test without the physical rover. I've led teams since my first year, and I care about clean architecture, good debugging habits, and making technical work easy for others to pick up.

</details>

## 🎯 Professional Goal

To build a career in Computer Engineering in space tech and robotics, writing reliable software for systems that have to work in the real world.

---

## 💼 Experience

<details>
<summary><b>🚀 UBC Rover: Software Team Lead</b> <i>(Sep 2023 – Present)</i></summary>
<br>

Software lead on UBC's Mars rover design team.

- Led a team implementing **CAN bus** communication for real-time rover arm and end-effector control, programming microcontroller peripherals and interrupts, improving control-loop reliability by **27%** (C++)
- Debugged faults across layers, from signal integrity up to ROS 2 application behaviour, using oscilloscopes and logic analyzers
- Cut hardware testing cycles by **45%** with Linux-based sensor simulation pipelines for validating motor control and perception data
- Built Unity simulations driven by GNSS/GPS data to replicate rover movement over real terrain

</details>

<details>
<summary><b>🏥 Emerging Media Lab, UBC: Software Developer & Team Lead</b> <i>(May 2025 – Dec 2025)</i></summary>
<br>

Worked on a VR OSCE training simulation for nurse practitioners, built in Unreal Engine.

- Cut system latency by **32%** by profiling and optimizing C++ and Python modules
- Built an AI speech-to-response pipeline for an interactive MetaHuman patient, with system-prompt guardrails, cutting end-to-end latency by **87%** (120s → 15s)
- Coordinated a multi-contributor Unreal codebase using Perforce

</details>

<details>
<summary><b>🔒 OneOS Research, UBC: Research Assistant</b> <i>(May 2025 – Jun 2025)</i></summary>
<br>

- Built a demo app for an experimental privacy-focused OS layer, showcasing camera blocking, role-based notifications, and visual privacy modes
- Designed a real-time alert system for sensitive resource access and wrote onboarding docs for new researchers

</details>

<details>
<summary><b>🌍 Learning Buddies Network (NGO): IT Team Member</b> <i>(Sep 2021 – Present)</i></summary>
<br>

- Led a website redesign for accessibility, improving usability by **40%**
- Built SQL + Pandas pipelines to track student engagement for program coordinators

</details>

---

## 🤔 What I'm Up To

### ⭐ Personal Projects

<details>
<summary><b>🤖 FastAPI Docs Assistant: RAG Pipeline</b></summary>
<br>

**Tech:** Python, ChromaDB, Streamlit, Groq API

- Agentic RAG backend that chunks 71 documents into 770 header-based chunks, embeds them with all-MiniLM-L6-v2, and retrieves the top 3 from ChromaDB
- Generates grounded, cited answers using an LLM (Groq API) strictly from retrieved context
- Evaluated on a 20-question ground-truth set: **90% SourceHitRate@3**

🔗 [View repo](https://github.com/ultimate-patronum/rag-docs-assistant)

</details>

<details>
<summary><b>📡 Embedded Sensor Acquisition System</b></summary>
<br>

**Tech:** C, FreeRTOS, SPI, UART, RP2040

- 3-task FreeRTOS pipeline with a mutex-protected SPI bus and interrupt-driven (ISR-to-task) sensor notification at 100 Hz
- Validated task restart through fault injection and watchdog recovery; profiled per-task CPU usage with FreeRTOS runtime stats

🔗 [View repo](https://github.com/ultimate-patronum/freertos-eeg-pipeline)

</details>

<details>
<summary><b>📅 Planify Scheduler App</b></summary>
<br>

**Tech:** React, Node.js, SQL, Docker

- Full-stack scheduler integrating transit APIs with academic calendars, reducing planning time by 34%
- Dockerized with CI/CD-driven deployment and automated UI tests


</details>

<details>
<summary><b>🍽️ Food Redistribution App: YouCode Hackathon</b></summary>
<br>

**Tech:** React, Android, JavaScript, HTML, CSS

- Connects restaurants with homeless shelters to redistribute surplus food, with inventory tracking and an automated recipe generator
- Demoed as a full-stack MVP within 24 hours


</details>

### 🏫 UBC Projects: *Code access is available upon request*

<details>
<summary><b>🏎️ Autonomous RC Car: RGBD/LiDAR Perception + PID Control</b></summary>
<br>

**Tech:** C++, Python, ROS 2, RTOS

- Placed **1st in the class competition** with a full autonomous stack built from scratch
- Custom RGBD/LiDAR perception for obstacle detection and lane tracking, plus a hand-built PID control loop with sub-100ms fault response, deployed on an RTOS via ROS 2

</details>

<details>
<summary><b>🖥️ OS/161 Kernel Extensions</b></summary>
<br>

**Tech:** C, UNIX/Linux, MIPS

- Implemented `fork()`, `execv()`, and `waitpid()` in a partnered project extending the OS/161 teaching kernel
- Worked through code review across virtual memory and file system components

</details>

<details>
<summary><b>🔌 Audio Streaming System: Flash Memory Interface (FPGA)</b></summary>
<br>

**Tech:** VHDL, Verilog, Quartus, ModelSim

- FSM-controlled flash memory interface on an Intel DE1-SoC, resolving clock domain crossing between 50 MHz and 27 MHz clocks
- Verified timing with ModelSim simulation and SignalTap in-system analysis

</details>

<details>
<summary><b>⚡ CUDA Parallelization & GPU Computing</b></summary>
<br>

**Tech:** C++, CUDA, cuRAND

- SAXPY and Monte Carlo π kernels with full GPU memory management and on-device random number generation
- Parallel reduction kernel aggregating 1B+ per-thread hit counts entirely on the GPU

</details>

<details>
<summary><b>🧠 Custom Memory Allocator</b></summary>
<br>

**Tech:** C

- Reimplemented `malloc`/`free` from scratch with a doubly linked free list, block splitting, coalescing, and alignment handling

</details>

---

## 🏅 Awards & Leadership

- **IEEE UBC Student Branch:** Student Life Lead (Sep 2026 – Present)
- **UBC Girls in STEAM**: Sponsorship Co-Director (Sept 2025 - Present)
- **Teaching Assistant, UBC MATH 110** (Sep 2025 – Dec 2025)
- **SPEAT BC Scholarship (2023):** STEM education and leadership contributions
- **School Community and Leadership Award (2023):** 300+ volunteer hours

---

## 👀 Where to Find Me!

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ultimate-patronum)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riddhima-gupta081)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:riddhimagupta1208@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/home?dmr=1&ec=wgc-drive-%5Bmodule%5D-goto)
