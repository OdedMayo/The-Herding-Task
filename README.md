
# 🐑 The Herding Task – Unity Project

This repository contains the Unity implementation of **The Herding Task**, a virtual dyadic coordination game built to study how synchrony and segregation demands affect behavioral alignment between two participants. The task was developed as part of an experimental study and is inspired by the bi-agent sheep herding game by Nalepka et al. (2017).

## 🎮 Task Overview

In this game, two participants work together to herd virtual sheep into a central containment zone while also collecting independently placed targets on their respective sides of the screen. The sheep respond to proximity by moving away from the sheepdogs, and the game is scored in real time based on target collection and sheep containment.

The task introduces structured **synchrony** (sheep herding) and **segregation** (target collection) demands through a 2×2 within-subject experimental design that manipulates:

- **Sheep speed** (higher = more coordination needed)
- **Target frequency** (higher = more independent action needed)

## 🧪 Experimental Design

Each dyad completes four randomized 2-minute conditions:

1. **Low sheep speed, low target frequency** (low synchrony, low segregation)
2. **Low sheep speed, high target frequency** (low synchrony, high segregation)
3. **High sheep speed, low target frequency** (high synchrony, low segregation)
4. **High sheep speed, high target frequency** (high synchrony, high segregation)

### 🧠 Training Phases

Participants go through three training phases:

1. **Sheep Only** – Contain all sheep for 30 seconds.
2. **Targets Only** – Collect 6 targets without sheep.
3. **Full Task** – Practice both tasks with scoring:
   - +1 point per collected target
   - -3 points per escaped sheep

## 🕹️ Controls

- **Player 1** (Right side):
  - Move around sheep: `Arrow Up` / `Arrow Down`
  - Collect targets: `Arrow Left` / `Arrow Right`

- **Player 2** (Left side):
  - Move around sheep: `W` / `S`
  - Collect targets: `A` / `D`

- **Switch screen** (e.g., in multi-phase experiments): `B`

## 🚀 How to Run

1. Open this project in **Unity 2018.2 beta** (or compatible).
2. Load the main scene from the `Assets/` folder.
3. Press **Play** in the Unity Editor.
4. Use two keyboards or a shared keyboard to control both players.

## 📁 Project Structure

Assets/
Packages/
ProjectSettings/


> Note: The `.gitignore` excludes all auto-generated Unity folders like `Library/`, `obj/`, `Temp/`, and build artifacts.

## 📜 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute it for academic or educational purposes, with attribution.

## 📄 Citation

If you use or adapt this task in your work, please cite:

- Mayo, O., Gordon, I. (under review). Contextual Pulls for Synchrony and Segregation: An Empirical Test of a Novel Theoretical Framework.

## 👨‍🔬 Contact

**Oded Mayo**  
✉️ ma.oded@gmail.com


