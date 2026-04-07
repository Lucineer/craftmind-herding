# Craftmind Herding

A herding simulation where AI sheepdogs, guided by player commands, manage flocks of sheep in a Minecraft environment. Train and observe autonomous agents that develop skills and exhibit distinct personalities through emergent, unscripted behavior.

---

## Purpose

This project provides a sandbox to experiment with multi-agent AI systems in a tangible, observable way. Adjust individual agent parameters and immediately see the effects on group dynamics and task performance within a simulated environment.

## How It Operates

*   Hosted entirely on Cloudflare Workers. No local installation, GPUs, or complex dependencies required.
*   Fork-first development. You are encouraged to copy, modify, and run your own version.
*   Transparent logic. All agent decision-making is implemented in readable, open code.
*   Built for the Cocapn Fleet, an open-source agent runtime.

**Live Instance:** https://the-fleet.casey-digennaro.workers.dev
Join an active session or deploy your own agent directly from the interface.

---

## Quick Start

1.  **Fork** this repository.
2.  **Deploy** it to Cloudflare Workers.
3.  **Modify** the simulation parameters, agent traits, or behaviors in the source code.

## Core Components

A herding simulation built for the Cocapn Fleet, combining boids-based flock mechanics with personality-driven dog agents.

### Simulation Features

*   **Flock Mechanics:** Configurable boids simulation (separation, alignment, cohesion).
*   **Agent Progression:** A five-tier system (Apprentice to Elder) that grants permanent stat modifiers.
*   **Personality Matrix:** Six adjustable axes (Speed, Patience, Obedience, Social, Bravery, Gentleness) that define unique agent behaviors.
*   **Dynamic Coordination:** Unscripted, emergent teamwork between multiple dog agents.
*   **Environmental Effects:** A seasonal weather system that influences movement and visibility.
*   **Standardized Courses:** Five herding courses with scoring and ratings.

## Extension

The system is designed to be modified. You can adjust the core flocking algorithms, introduce new personality traits, create custom courses, or adapt the agent logic for other environments.

**One Current Limitation:** The simulation's complexity is bound by the computation limits of the edge runtime. Extremely large flock or agent counts may require optimization.

## Contributing

The project follows a fork-first model. To contribute, fork the repository, implement your changes, and if you create something you believe benefits others, open a pull request.

---

MIT License · Superinstance & Lucineer (DiGennaro et al.)

<div align="center">
  <a href="https://the-fleet.casey-digennaro.workers.dev">The Fleet</a> · 
  <a href="https://cocapn.ai">Cocapn</a>
</div>