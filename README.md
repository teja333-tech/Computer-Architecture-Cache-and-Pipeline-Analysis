# Computer-Architecture-Cache-and-Pipeline-Analysis
Study of cache block size effects using gem5 and load-use hazard analysis using RIPES in Computer Organization &amp; Architecture.

# Computer Organization & Architecture Project

## Cache Performance Analysis using gem5 & Pipeline Hazard Analysis using RIPES

---

## Overview

This project analyzes two important concepts of Computer Organization and Architecture:

- Cache Memory Performance Analysis using the **gem5 Simulator**
- Pipeline Hazard Analysis using the **RIPES Simulator**

The objective is to understand how cache block size affects processor performance and how forwarding reduces pipeline stalls caused by load-use hazards.

---

## Objectives

- Analyze cache performance for different cache block sizes.
- Measure cache miss rate.
- Measure execution time.
- Study load-use hazards in a pipelined processor.
- Analyze cycle penalty with and without forwarding.

---

## Tools Used

- gem5 Simulator
- RIPES Simulator
- C Programming
- GCC Compiler
- Linux Command Line

---

# Project 1: Cache Performance Analysis

### Cache Block Sizes Tested

- 16 Bytes
- 32 Bytes
- 64 Bytes

### Parameters Measured

- Cache Miss Rate
- Execution Time

---

## Results

| Cache Block Size | Execution Time | Miss Rate |
|-----------------|---------------|-----------|
| 16B | 0.000304 s | 0.038683 |
| 32B | 0.000304 s | 0.022942 |
| 64B | 0.000304 s | 0.014231 |

### Observation

Increasing cache block size reduces cache miss rate due to improved spatial locality.

The 64-byte cache block produced the lowest miss rate.

---

# Project 2: Pipeline Hazard Analysis

A Load-Use Hazard was analyzed using the RIPES simulator.

The experiment compares processor execution with:

- Forwarding Disabled
- Forwarding Enabled

### Results

| Configuration | Clock Cycles |
|--------------|--------------|
| Forwarding Disabled | 10 |
| Forwarding Enabled | 9 |

### Cycle Penalty

Cycle Penalty = 10 − 9 = **1 Cycle**

---

## Key Concepts

- Cache Memory
- Spatial Locality
- Cache Miss Rate
- Pipeline
- Load-Use Hazard
- Data Hazard
- Forwarding
- Cycle Penalty

---

## Folder Structure

```
COA Project/
│
├── Source_Code/
├── Screenshots/
├── Results/
├── Presentation/
└── README.md
```

---

## Learning Outcomes

- Understood cache hierarchy.
- Learned memory access optimization.
- Simulated cache behavior using gem5.
- Visualized pipeline execution in RIPES.
- Studied forwarding and hazard handling.
- Compared processor performance under different configurations.

---



## Course

Computer Organization & Architecture (COA)

B.Tech Computer Science Engineering
