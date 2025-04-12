# 🚦 Four-Way Intersection Traffic Signal – LogicWorks Simulation

### A Digital Logic Design Course Project  
**Team Members**: Huzaifa, Shoaib, Ghufran  
**University**: FAST-NUCES Karachi 
**Semester**: Spring 2025  
**Course**: Digital Logic Design  
**Tool Used**: LogicWorks 5

---

## 📘 Project Overview

This project is a digital circuit simulation of a **four-way traffic intersection** using **LogicWorks**, designed for our Digital Logic Design course. The system models how traffic lights operate at a cross intersection, including timer-controlled signals and directional priority logic.

The goal was to apply FSM design, counters, and combinational logic in a real-world-inspired scenario, simulating how traffic is managed in a timed and prioritized manner.

---

## 🛠️ Features

- 🧠 **Finite State Machine (FSM)** based light control  
- ⏱️ Timer simulation using counters and clocks  
- 🟢🟡🔴 LED indicators for each traffic direction (North, South, East, West)  
- ⚡ Clock pulse-driven state transitions  
- 🛣️ Priority handling (e.g., NS direction gets higher priority over EW)  

---

## 🧱 LogicWorks Design Components

| Component        | Purpose                                           |
|------------------|---------------------------------------------------|
| **Flip-Flops**   | Store FSM states                                  |
| **Counters**     | Implement timers for green/yellow light durations |
| **LEDs**         | Indicate signal color (Green/Yellow/Red)          |
| **Clocks**       | Drive timed state changes                         |
| **Logic Gates**  | Determine next-state logic and output signals     |

---

## 🔄 How the Circuit Works

1. **Initialization**: All directions are red for a moment during system reset.
2. **Signal Cycle**: Each direction gets a turn with green, followed by yellow, then red.
3. **Timers**: Light durations are managed by binary counters connected to a system clock.
4. **Priority Logic**: When timing overlaps or conflicts, NS direction has priority in state transition logic.
5. **Looping**: The system runs continuously in a loop to simulate real-time traffic light behavior.

---
