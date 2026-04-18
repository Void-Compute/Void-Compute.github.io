
  
# 👻 GHOST
**GPU Hardware Operating Software Translator**

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Issues](https://img.shields.io/badge/Issues-0_Open-success)](#)
[![Clones](https://img.shields.io/badge/Clones-400%2B-orange)](#)
[![Status](https://img.shields.io/badge/Status-Production_Ready-brightgreen)](#)

*Breaking hardware monopolies through low-level systems architecture.*

[Documentation](#) • [Roadmap](#-architecture--roadmap) • [Devlog](#-developer-log) • [Community Forum](#-community--support)


---

## 🌌 Overview
GHOST is a hardware-agnostic translation layer designed to intercept and route compute instructions across disparate GPU architectures. It enables standard, high-performance execution of proprietary ML workloads on non-native silicon without virtualization overhead.

In short: **Write once. Run anywhere. Let the logic handle the translation.**

## ✨ Core Features
* **CUDA on AMD:** Allows AMD GPU's to run CUDA only software via ZLUDA
* **VRAM Leak Prevention:** Custom hardware-state checks bypass standard async race conditions.
* **Decoupled Architecture:** Hardware tracks (AMD, Intel, Apple) are strictly isolated to prevent dependency hell.
* **Waiting Room TUI:** While the AI's are loading you can either play music or play a fully working version of DOOM ASCII in your Terminal


##  Architecture & Roadmap
GHOST is built on a modular, microservice-inspired philosophy. Our primary focus is platform hardening before horizontal expansion.

### Phase 1: The AMD Core (Current)
- [x] Windows Port Stabilization
- [x] ROCm / HIP execution logic
- [x] Multi-node VRAM routing
- [x] RX 7000 / 9000 Series Mapping 

### Phase 2: Heterogeneous Expansion (R&D)
- [ ] **Intel Track:** oneAPI / Level Zero integration (SYCL).
- [ ] **Apple Track:** Metal Performance Shaders / MLX routing for Unified Memory Architectures.

### Phase 3: Silicon Re-Architecting (Future)
- [ ] **Core-Stripped NPU:** Repurposing standard GPU Compute Units (CUs) for dedicated, direct-to-ALU AI inference.

---

## Installation & Quick Start

```bash
# Clone the verified production branch
git clone [https://github.com/Void-Compute/AMD-Ghost-Enviroment.git](https://github.com/Void-Compute/AMD-Ghost-Enviroment.git)

# Initialize the translation layer
cd AMD-Ghost-Enviroment
chmod +x bin/ghost
```
To initialize the system:

 1. Open your File Explorer.
 2. Navigate to the Ghost folder.
 3. Double-click the 'ghost' script file.      (Choose 'Run in Terminal' if prompted).
The environment will automatically resolve the correct directory, activate your Python venv, and apply all AMD/NVIDIA spoofing masks.

On your first run, the First-Startup Wizard will ask you which AI tool you are using and automatically download the ZLUDA translation engine.


-----

## 📜 Developer Log (Devlog)

We believe in building in public.

  * **v2.0.1 (Latest):** Massive architecture update. Implemented hardware-state failsafes to resolve venv auto-activation bugs. Hardened the logic gates for RDNA 4 anticipation.
  * **v1.5.0:** Fixed GFX Version spoofing for RX 9000 series.
  * **v1.0.0:** Initial Windows translation layer launched. SDMA bottleneck resolved.

-----

## 💬 Community & Support

GHOST is a community-driven ecosystem. If you are running into scale-specific entropy (like multi-GPU synchronization deadlocks), join the discussion.

  * **[The GHOST Forum (GitHub Discussions)](https://github.com/Void-Compute/AMD-Ghost-Enviroment/discussions)** - Best for architectural questions and PR submissions.
  * **[Discord Community (coming soon)](https://www.google.com/search?q=%23)** - Real-time debugging and playground scaling.

-----



*Built with precision in Germany.* <br>
**[Explore the GHOST Ecosystem on GitHub](https://github.com/Void-Compute)**



-----

