# Electricity & Semiconductors: From Atoms to Datasheets

A self-paced course built as Jupyter notebooks. The end goal: you can pick up **any semiconductor datasheet** and understand what it's telling you.

## Prerequisites

- Basic algebra (solving equations, reading graphs)
- Curiosity about how electronics actually work
- Willingness to build physical circuits

## Equipment

| Item | Notes |
|------|-------|
| Klein MM300 multimeter | DC/AC voltage, current, resistance, continuity |
| Fnirsi 2C53T oscilloscope | 2-channel + built-in signal generator |
| Bench power supply | 0–30 V, 0–10 A adjustable |
| Breadboard | Full-size, 830 tie points recommended |
| Jumper wire kit | Male-male at minimum |

See **[shopping-list.md](shopping-list.md)** for the complete parts list.

## Course Structure

| Module | Topic | Lessons |
|--------|-------|---------|
| **00** | Foundations | Electrical fundamentals, AC vs DC & signals |
| **01** | Before Semiconductors | Conductors/insulators, vacuum tubes |
| **02** | PN Junctions | Doping, diodes, Zener diodes, *Datasheet Drill: 1N4148* |
| **03** | Transistors (BJT) | How BJTs work, switch/amplifier, Darlington, *Datasheet Drill: 2N3904* |
| **04** | MOSFETs | Field effect, experiments, MOSFET vs BJT, *Datasheet Drill: IRFZ44N* |
| **05** | Semiconductor Zoo | Optoelectronics, power/regulation, sensors, *Datasheet Drill: LM358* |
| **06** | Integrated Circuits | Transistors to gates, logic families, *Datasheet Drill: 74HC00* |
| **07** | Capstone | Datasheet reading methodology, capstone project |

Every module ends with a **Datasheet Drill** — a dedicated notebook that walks through a real manufacturer datasheet section-by-section, explaining every parameter, graph, and table.

## Getting Started

```bash
# Clone the repo
git clone <repo-url>
cd electricity-and-semiconductors-course

# Install dependencies with uv
uv sync

# Launch Jupyter
uv run jupyter lab
```

Then open `module-00-foundations/00-electrical-fundamentals.ipynb` and begin.

## Design Philosophy

- **Python is for plotting and calculating**, not circuit simulation. Physical experiments and [Falstad](https://www.falstad.com/circuit/) links handle simulation.
- **Every notebook is self-contained** — theory, experiment, simulation link, datasheet connection, and checkpoint questions.
- **Experiments use real equipment** — oscilloscope exercises where waveforms matter, multimeter exercises for DC measurements.
- **The core skill is datasheet literacy** — every concept connects back to "here's where this shows up on a real datasheet."
