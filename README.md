# Replication-to-TombeZhu 
This project traces the evolution of international trade models from the **Ricardo model** to the **Eaton-Kortum (EK) model**, followed by a replication to Tombe & Zhu (2019).

The repository integrates theoretical exposition with executable code, demonstrating how the field moved from a qualitative 2x2 model to a fully quantifiable multi-country general equilibrium framework.

## Key Models

| Model | Core Idea | Quantifiability |
|-------|-----------|------------------|
| **Ricardo** | Labor productivity differences determine trade patterns | Limited (qualitative/comparative statics) |
| **DFS (1977)** | Continuum-of-goods extension of Ricardo; equilibrium determined by cutoff good | Intermediate (closed-form solutions for relative wages) |
| **Eaton-Kortum (2002)** | Continuous goods continuum + Fréchet productivity draws | High (matches actual trade flows) |

## What's Included

- **Theory**: Concise notes on model setup, equilibrium conditions, and key derivations
- **Code**: Numerical simulations
- **Application**: Replication to Tombe & Zhu (2019)

## Technologies

Python + standard numerical libraries

## Quick Start

```bash
git clone <repo-url>
cd ricardo-to-ek
python code/ek_replication.py   # to be determined
