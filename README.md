# Sentinel Swarm: A Bio-Inspired Simulation

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![Libraries](https://img.shields.io/badge/Libraries-NumPy%20%7C%20Matplotlib-orange)](https://numpy.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

This repository contains the implementation of a **Fish Swarm Algorithm (FSA)** to solve a multi-target search and neutralization problem, inspired by collective behavior in nature and the *Matrix* film universe.

## 🧠 Project Overview

The project simulates a swarm of autonomous agents ("Sentinels") that must efficiently locate and neutralize multiple targets ("Aerodeslizadores") in a fog-covered area. One target is a low-quality decoy, adding a layer of complexity. The Sentinels autonomously coordinate using bio-inspired behaviors from the FSA:

- **Search/Prey Behavior:** Individual exploration of the environment.
- **Swarming Behavior:** Movement towards the centroid of nearby Sentinels to avoid over-crowding.
- **Following Behavior:** Tracking peers that have found high-quality targets.
- **Random Behavior:** Ensuring exploration and avoiding local optima.

The simulation visualizes the swarm's collective intelligence as it converges on targets, demonstrating a robust solution to complex optimization and coordination challenges.

## 🚀 Features

- **Full FSA Implementation:** Complete implementation of the Fish Swarm Algorithm with all four core behaviors.
- **Interactive Visualization:** Real-time animation built with `matplotlib` showing agent movement, detection radii, and target neutralization.
- **Matrix-Themed Scenario:** A fun and engaging context based on the Sentinel swarms from *The Matrix*.
- **Configurable Parameters:** Easily adjust the number of agents, visual range, step size, and neutralization thresholds.
- **Performance Tracking:** Live counters and status updates track progress towards neutralizing each target.
