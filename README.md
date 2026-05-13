
# Dynamic Market Engine — Equilibrium Simulator

## Overview

Dynamic Market Engine is an interactive 3D computational economics simulator designed to model market equilibrium behavior under stochastic and policy-driven conditions. The project combines real-time visualization, agent-based simulation, and economic equilibrium modeling to explore how dynamic supply-demand systems respond to external shocks, taxation policies, and behavioral trade activity.

The simulator was developed as an experimental research-oriented platform to investigate the intersection of computational modeling, economic systems, interactive visualization, and adaptive simulation architectures using modern web technologies.

The system integrates:
- Real-time equilibrium computation
- Agent-based market interactions
- Stochastic trade behavior
- Dynamic policy interventions
- Interactive economic shock simulations
- GPU-accelerated 3D rendering

The project draws conceptual inspiration from computational economics, systems simulation frameworks, and interactive educational visualization environments.

---

## Research Motivation

Modern economic systems increasingly rely on computational models to simulate nonlinear interactions between agents, policies, and market structures. Traditional static visualizations often fail to capture the emergent behavior and instability introduced by dynamic market conditions.

This project explores:
- Emergent equilibrium behavior
- Market instability under external shocks
- Interactive policy experimentation
- Computational visualization of economic systems
- Agent-driven stochastic simulations
- Real-time educational simulation interfaces

The simulator also serves as an experimental foundation for future work involving:
- Sustainable economic modeling
- AI-assisted market simulations
- Reinforcement learning environments
- Multi-agent adaptive systems
- Behavioral economic simulation frameworks

---

## Core Features

### Real-Time Equilibrium Solver
Implements dynamic supply-demand equilibrium calculations using continuously adjustable market parameters.

### Agent-Based Simulation
Simulates buyer and seller populations with stochastic movement patterns and trade interactions.

### Interactive Policy Controls
Supports dynamic modification of:
- Taxation systems
- Subsidies
- Supply curves
- Demand curves
- Trade frequency
- Population scaling

### Economic Shock Engine
Includes real-time simulation events such as:
- Pandemic-induced demand collapse
- Technological supply expansion
- Carbon tax policy interventions

### 3D Visualization Layer
Built using Three.js to provide:
- Interactive orbital navigation
- Real-time equilibrium rendering
- Trade pulse visualization
- Projection analysis
- Particle-based market agents

### Educational Simulation Environment
Designed as a visual learning environment for:
- Computational economics
- Dynamic systems analysis
- Market behavior studies
- Economic policy experimentation

---

## Technical Architecture

### Frontend Stack
- HTML5
- CSS3
- JavaScript (ES6 Modules)

### Visualization & Rendering
- Three.js
- WebGL
- OrbitControls
- lil-gui

### Simulation Components
- Dynamic equilibrium computation
- Stochastic agent movement
- Event-driven shock modeling
- Real-time parameter adjustment

---

## Mathematical Foundation

The simulator models equilibrium using linear supply-demand equations:

Demand:
P = a - bQ

Supply:
P = c + dQ + T - S

Where:
- P = Price
- Q = Quantity
- T = Tax
- S = Subsidy

Equilibrium is computed dynamically as:

Q* = (a - c - T + S) / (b + d)

The framework continuously recalculates equilibrium states in real time during simulation execution.

---

## Simulation Modules

### Market Curves
Dynamically rendered supply and demand structures with adjustable parameters.

### Agent Dynamics
Autonomous market participants exhibiting randomized yet curve-biased movement behavior.

### Trade Pulse System
Visual representation of successful market transactions near equilibrium conditions.

### Shock Simulation Engine
Implements transient macroeconomic disturbances affecting equilibrium stability.

---

## Potential Research Extensions

Future extensions may include:
- Reinforcement learning agents
- Adaptive pricing systems
- Neural economic forecasting
- Carbon-aware economic simulations
- Sustainable economic optimization models
- Multi-market interaction systems
- Distributed economic networks
- AI-governed market regulation models

---

## Academic Relevance

This project aligns with research areas including:
- Computational Economics
- Agent-Based Modeling
- Complex Adaptive Systems
- Interactive Simulation Systems
- Economic Visualization
- Human-Computer Interaction
- AI-Augmented Simulation Environments
- Sustainable Digital Systems

---

## Running the Project

Clone the repository:

```bash
git clone [repository-link]
````

Open the project directory and launch using a local development server.

Example:

```bash
python -m http.server
```

Then open:

```text
http://localhost:8000
```

---

## Controls

| Action            | Interaction  |
| ----------------- | ------------ |
| Orbit Camera      | Left Mouse   |
| Zoom              | Scroll Wheel |
| Pan View          | Right Mouse  |
| Modify Parameters | GUI Panel    |

---

## Author

Rahul Kiran G

Independent Researcher focused on:

* Sustainable AI
* Responsible AI
* Computational Systems
* AI-Enabled Educational Technologies
* Interactive Simulation Environments
* Sustainable Software Engineering

---

## License

This project is intended for academic, educational, and research-oriented experimentation.

```
```
