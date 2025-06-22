# 🧬 Synthetic Biology Project Portfolio

A curated portfolio of beginner-to-intermediate level dry lab projects in synthetic biology. Each project is coded in Python using Tellurium and Antimony, and simulates gene circuits relevant to iGEM-style work.

---

## 🔬 Projects

### 1. [Basic Gene Expression](https://github.com/gene-arch/basic-gene-expression)
Simulates fundamental gene expression: DNA → mRNA → Protein, using Tellurium. It models a minimal genetic circuit to understand transcription and translation dynamics.

> **Skills:** Antimony modeling, time-course simulation, matplotlib plotting

---

### 2. [Inducible Gene Expression](https://github.com/gene-arch/inducible-gene-expression)
Models a system where gene expression is controlled by an external inducer. This simulates a toggle-style repression system showing protein output suppression in response to inducer presence.

> **Skills:** Repressor-based circuit modeling, inducible response logic, kinetics simulation

---

### 3. [Inducer Dose Response Simulation](https://github.com/gene-arch/inducer-dose-response-simulation)
Performs a parameter sweep to explore the effect of varying inducer concentrations on protein output. Visualizes how different doses impact gene circuit behavior.

> **Skills:** Parameter sweeping, matplotlib graphing, synthetic dose-response curve generation

---

### 4. Toggle Switch Simulation

This simulation models a genetic toggle switch built from two genes that repress each other. Depending on initial conditions and parameter tuning, the system stabilizes in one of two possible states. It demonstrates bistability — a core concept in synthetic biology for creating memory circuits and biological logic systems. No external signal is used in this version.

> Code for this circuit can be found in the files uploaded in this repositery under the name of toggle_test

---

### 5. IPTG-Inducible Toggle Switch

This simulation extends the classic toggle switch by introducing IPTG as an external input signal. When IPTG is present, it inhibits one of the repressors, allowing the circuit to flip into a new state. Even after the signal is removed, the system retains its ON state — demonstrating memory-like behavior. This models how cells can record past exposure to specific signals.

> Code for this circuit can be found in the files uploaded in this repositery under the name of IPTG_toggle

---

### 6. Synthetic Genetic AND Gate (Dual Input Control)

This simulation models a genetic AND gate, where a target gene is expressed only when both input signals are present. The system mimics digital logic using biological components, combining two separate inducers to control a single output. It demonstrates how synthetic circuits can implement Boolean logic in living systems — a key feature in biosensors and programmable cells.

> Code for this can be found in the files uploaded in this repositery under the name of AND_Gate

---

### 7. Synthetic Genetic NOT Gate (Signal Repression)

This simulation models a genetic NOT gate, where the presence of an input signal represses the output gene. When the input is absent, the output is high; when the input is present, the output is turned off. This simple but powerful logic structure is widely used in constructing more complex synthetic circuits like toggles, switches, and biosensor cascades.

> Code for this can be found in the files uploaded in this repositery under the name of NOT_Gate

---

### 8. Synthetic Genetic NAND Gate (Dual-Repression Logic)

This simulation models a genetic NAND gate, where the output gene remains active unless both input signals are present simultaneously. The system uses dual repression to ensure that the output is only turned off under combined input conditions. As a universal logic gate, NAND can be used to construct any other logic function, making it a powerful component in synthetic biology circuit design.

> Code for this can be found in the files uploaded in this repositery under the name of NAND_Gate

---

### 9. Time Delay Output Circuit

This simulation models a genetic circuit where an output protein (GFP) is only expressed after a delay, requiring the accumulation of an intermediate species. This demonstrates how synthetic systems can introduce controlled response lags using transcriptional cascades. Useful for modeling biological buffering, temporal gating, or delayed activation.

> Code for this can be found in the files uploaded in this repositery under the name of time_delay_output

---

### 10. Pulse Filter Circuit

This simulation models a genetic circuit which filters out short, transient input signals and only allows sustained stimuli to activate the output. Mimics biological systems that ignore noise or spikes, ensuring GFP is only expressed when the input (e.g., IPTG) exceeds a duration threshold. Useful for building noise-resistant or persistence-sensitive genetic devices.

> Code for this can be found in the files uploaded in this repositery under the name of pulse_filter

---

### 11. FeedForward Loop (FFL)

This simulation models a genetic circuit which implements a genetic motif where the input regulates the output both directly and indirectly through an intermediate. This creates a delay in activation or repression depending on the logic type (coherent or incoherent). Demonstrates dynamic filtering, pulse generation, or buffering — commonly found in natural transcriptional networks.

> Code for this can be found in the files uploaded in this repositery under the name of feedfoward_loop

---

### 12. AHL-Triggered Incoherent Feedforward Loop (IFFL)

This simulation models a genetic circuit where AHL acts as the input trigger, activating both the output (GFP) and a repressor that eventually shuts it down. This creates a sharp, transient GFP pulse despite continued AHL presence. Models temporal filtering and fast response-reset behavior — useful for detecting brief signals or generating pulses in synthetic circuits.

> Code for this can be found in the files uploaded in this repositery under the name of AHL-triggered_IFF_Loop

---

### 13. Ramp Generator Circuit

This simulation models a circuit which produces a gradual, linear-like increase in GFP expression over time in response to a constant input. Achieved by controlling feedback strength and degradation rates. Useful for modeling systems requiring slow accumulation, dose-dependent responses, or time-scheduled gene activation in synthetic biology applications.

> Code for this can be found in the files uploaded in this repositery under the name of ramp_generator

---

### 14. Threshold-Activated Toggle Switch

This simulation models a genetic circuit which has a bistable circuit that remains OFF at low input levels but flips ON once a critical IPTG threshold is crossed. Uses mutual repression and input-triggered derepression to lock the system in a stable ON state. Demonstrates switch-like behavior, signal memory, and threshold-based activation — key principles in genetic logic design.

> Code for this can be found in the files uploaded in this repositery under the name of Threshold-activated_toggle_switch

---


## ⚙️ Tools & Technologies

- **Tellurium** (Python-based simulation)
- **Antimony** (model definition language)
- **matplotlib** (data visualization)
- **Jupyter Notebook** & **VS Code**

---

## 🎯 Purpose

This portfolio showcases my independent dry lab work as a first-year synthetic biology enthusiast. It highlights my growing skills in modeling, simulation, and synthetic circuit analysis — essential for future contributions to iGEM and research-driven biotech roles.

---
