# RISC-V-Edge-AI-with-VSDSquadron-Pro

# Course Project

## 📌 Overview
This repository documents my progress through the **RISC-V Edge AI with VSDSquadron PRO** course by **VLSI System Design (VSD)**.  
The course is centered on implementing **machine learning (ML) and neural networks** on a highly resource-limited platform — the **SiFive FE310-G002 RISC-V SoC** with only **16 KB RAM**.  

Since I did not have access to the physical board, the entire workflow (training, quantization, inference, and image capture) was simulated using **Freedom Studio** for RISC-V bare-metal builds.

The core of this project is an **MNIST handwritten digit classifier**, trained and quantized in Python, and ported into a simulated bare-metal RISC-V environment for inference.

---

## 🎯 Objectives
- Train and quantize a neural network for **MNIST digit recognition**.  
- Optimize the model to fit **memory-constrained environments** (≤16 KB).  
- Simulate deployment on **SiFive FE310-G002** without requiring hardware.  
- Explore bare-metal programming concepts and memory-aware inference.  

---

## 📚 Course Modules (Highlights)
The course spans **27 learning modules**, progressing from basic ML to quantized NN deployment:

1. Edge AI introduction & VSDSquadron board overview  
2. ML basics – regression, gradient descent, visualization  
3. Classification – KNN, SVM, and embedded inference  
4. MNIST with SVM and RISC-V simulation  
5. Quantization & fitting AI into 16 KB RAM  
6. Neural networks – from scratch to 98% accuracy  
7. Bit-quantized NN deployment on RISC-V  

---

## 🛠 Hardware & Software Environment
**Target Hardware (simulated):**
- **SiFive FE310-G002** (RV32IMAC, 320 MHz, 16 KB L1 I-cache, 16 KB SRAM, QSPI Flash).  
- No physical board used — simulation only.  

**Tools & Software:**
- **VSCode** – main development IDE  
- **Python 3.10+** with:  
  - `tensorflow==2.15.0`  
  - `numpy`  
  - `matplotlib`  
- **Freedom Studio 3.1.1 (optional)** – RISC-V simulation/debugging  
- **RISC-V GNU Toolchain (optional)** – for compiling C code  

---

## 📂 Project Structure
