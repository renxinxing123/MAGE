# SAGE: Simulation via Agent-based Generative Engine

SAGE is a multi-agent pipeline that generates Simulink simulation code from input diagrams.  
It leverages large language models, multimodal perception, and modular agentic workflows.

## 🧠 Concept

Given a Simulink-style simulation diagram as input (image format), SAGE produces the corresponding MATLAB Simulink code and runs the simulation automatically.

## 🧩 Concept Diagram

![Concept Diagram](link-to-image-or-path-in-repo)

### System Overview

The system includes the following components:
- **Multimodal Investigator**: Detects blocks and connections from a simulation diagram.
- **Unit Test Reviewer**: Validates logical correctness of the extracted connections.
- **Block Builder**: Builds the simulation using `matlab.engine` in Python.
- **Debug Locator**: Identifies whether errors come from code logic or overlooked connection issues.

## 📺 Demo Videos

- [Demo 1: Generating a basic bouncing ball simulation](link-to-video-1)
- [Demo 2: Debugging a faulty block connection](link-to-video-2)
- [Demo 3: End-to-end pipeline demo](link-to-video-3)



## 🚧 Coming Soon
- Code release
- Documentation and setup guide
