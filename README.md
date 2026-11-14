<div align="center">

# <img src="https://api.iconify.design/lucide/circuit-board.svg?color=%236C63FF" width="34" height="34" align="absmiddle" alt="" /> LogicVerse

### From Silicon to Code: an interactive digital electronics learning platform

*Explore digital electronics through hands-on, visual simulations, from semiconductor physics all the way to CPU instruction execution.*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Course](https://img.shields.io/badge/Course-FOIDS-0A7B83?style=flat-square)](#-academic-information)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](#-credits--license)

[Overview](#-overview) · [Features](#-features) · [Learning Layers](#-the-six-learning-layers) · [Getting Started](#-getting-started) · [Structure](#-project-structure) · [Roadmap](#-roadmap)

</div>

---

## <img src="https://api.iconify.design/lucide/book-open.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> Overview

**LogicVerse** is a browser-based digital electronics learning platform built for the *Foundations of Intelligent Digital Systems (FOIDS)* course. It makes abstract concepts easier to grasp by letting you *see* and *interact* with them.

It combines two complementary simulators:

| Module | What it covers | Open |
|---|---|---|
| <img src="https://api.iconify.design/lucide/puzzle.svg?color=%236C63FF" width="18" height="18" align="absmiddle" alt="" /> **Logic Circuit Simulator** | Logic circuits, Boolean expressions, gate operations, truth tables and K-map tools | [`logic-simulator/index.html`](logic-simulator/index.html) |
| <img src="https://api.iconify.design/lucide/monitor.svg?color=%236C63FF" width="18" height="18" align="absmiddle" alt="" /> **Full Digital Electronics Simulator** | A guided journey from semiconductor physics to CPU execution | [`full-simulator/index.html`](full-simulator/index.html) |

No build step, no dependencies: just open it in a browser.

---

## <img src="https://api.iconify.design/lucide/sparkles.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> Features

### <img src="https://api.iconify.design/lucide/puzzle.svg?color=%236C63FF" width="20" height="20" align="absmiddle" alt="" /> Logic Circuit Simulator

- Interactive logic-circuit workspace
- Boolean-expression analysis
- Logic-gate operations
- Truth-table tools
- Boolean-expression simplification
- Karnaugh map (K-map) minimization
- Visual representation of digital logic

### <img src="https://api.iconify.design/lucide/monitor.svg?color=%236C63FF" width="20" height="20" align="absmiddle" alt="" /> Full Digital Electronics Simulator

- Six connected learning layers, each in its own module
- Visual exploration from semiconductor physics to instruction execution
- Fully browser-based interface

> **Note:** The exact availability of individual controls depends on the current implementation in the repository. Check each simulator before assuming every listed capability is complete.

---

## <img src="https://api.iconify.design/lucide/layers.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> The Six Learning Layers

The Full Simulator builds understanding from the ground up, with each layer resting on the one below it.

```mermaid
flowchart TD
    A["Layer 1<br/>Semiconductor Physics"] --> B["Layer 2<br/>Transistors"]
    B --> C["Layer 3<br/>Logic Gates"]
    C --> D["Layer 4<br/>Digital Circuits"]
    D --> E["Layer 5<br/>CPU Architecture"]
    E --> F["Layer 6<br/>Instruction Execution"]
```

| # | Layer | Learning focus |
|:-:|---|---|
| 1 | <img src="https://api.iconify.design/lucide/atom.svg?color=%236C63FF" width="18" height="18" align="absmiddle" alt="" /> Semiconductor Physics | Foundations of semiconductor devices |
| 2 | <img src="https://api.iconify.design/lucide/cable.svg?color=%236C63FF" width="18" height="18" align="absmiddle" alt="" /> Transistors | Transistors as electronic switches |
| 3 | <img src="https://api.iconify.design/lucide/circuit-board.svg?color=%236C63FF" width="18" height="18" align="absmiddle" alt="" /> Logic Gates | Basic digital gates and their operations |
| 4 | <img src="https://api.iconify.design/lucide/puzzle.svg?color=%236C63FF" width="18" height="18" align="absmiddle" alt="" /> Digital Circuits | Combining gates into larger circuits |
| 5 | <img src="https://api.iconify.design/lucide/cpu.svg?color=%236C63FF" width="18" height="18" align="absmiddle" alt="" /> CPU Architecture | Fundamental CPU components |
| 6 | <img src="https://api.iconify.design/lucide/cog.svg?color=%236C63FF" width="18" height="18" align="absmiddle" alt="" /> Instruction Execution | How instructions are processed and executed |

---

## <img src="https://api.iconify.design/lucide/target.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> Project Objectives

- Understand the fundamentals of digital electronics
- See how semiconductor devices form the foundation of digital systems
- Understand transistor switching
- Learn how logic gates operate
- Explore Boolean algebra and logic-circuit design
- Connect individual gates to larger digital systems
- Understand basic CPU architecture and instruction execution
- Support learning through visual demonstrations

---

## <img src="https://api.iconify.design/lucide/rocket.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> Getting Started

### Requirements

- A modern web browser (Chrome, Firefox, Edge or Safari)
- *Optional:* [Git](https://git-scm.com/) for cloning
- *Optional:* [VS Code](https://code.visualstudio.com/) with the Live Server extension

### Quick start

```bash
# 1. Clone the repository
git clone https://github.com/shreyas-landge/LogicLab.git

# 2. Enter the project directory
cd LogicLab
```

Then either:

- **Open the root `index.html`** in your browser, or
- **Use VS Code Live Server:** right-click `index.html` → *Open with Live Server*

### Jump straight to a simulator

| Simulator | Path |
|---|---|
| Logic Circuit Simulator | `logic-simulator/index.html` |
| Full Digital Electronics Simulator | `full-simulator/index.html` |

---

## <img src="https://api.iconify.design/lucide/folder-tree.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> Project Structure

```text
LogicLab/
├── index.html                  # Landing page
├── README.md
│
├── logic-simulator/            # Logic Circuit Simulator
│   ├── index.html
│   ├── app.js                  # App wiring and UI
│   ├── circuit.js              # Circuit workspace
│   ├── logic.js                # Gate and Boolean logic
│   ├── kmap.js                 # K-map minimization
│   ├── style.css
│   └── README.md
│
└── full-simulator/             # Full Digital Electronics Simulator
    ├── index.html
    ├── main.js
    ├── simulator.js
    ├── utils.js
    ├── style.css
    ├── layer1-physics.js
    ├── layer2-transistor.js
    ├── layer3-gates.js
    ├── layer4-circuits.js
    ├── layer5-cpu.js
    └── layer6-execution.js
```

---

## <img src="https://api.iconify.design/lucide/flask-conical.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> Learning Outcomes

By working through the implemented modules, you can study:

- Semiconductor fundamentals
- Transistor switching
- Basic and derived logic gates
- Boolean algebra
- Truth tables
- Sum of Products (SOP) and Product of Sums (POS)
- Minterms and maxterms
- Karnaugh map simplification
- Combinational digital circuits
- Basic CPU architecture
- Instruction-execution concepts

---

## <img src="https://api.iconify.design/lucide/wrench.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> Technology Stack

| Technology | Role |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling and layout |
| JavaScript | Interactive behavior and simulation logic |
| Git & GitHub | Version control and hosting |

---

## <img src="https://api.iconify.design/lucide/map.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> Roadmap

- [ ] Sequential-circuit simulations
- [ ] Flip-flops and registers
- [ ] Counters and shift registers
- [ ] Expanded CPU architecture demonstrations
- [ ] Guided experiments and practice exercises
- [ ] Improved simulation controls and visual explanations
- [ ] More interactive circuit components

---

## <img src="https://api.iconify.design/lucide/graduation-cap.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> Academic Information

| | |
|---|---|
| **Project** | LogicVerse: Interactive Digital Electronics Simulator |
| **Developer** | Shreyas Landge |
| **Subject** | Foundations of Intelligent Digital Systems (FOIDS) |
| **Program** | B.Tech, Artificial Intelligence and Data Science |
| **Institution** | Vishwakarma Institute of Technology, Pune |

---

## <img src="https://api.iconify.design/lucide/award.svg?color=%236C63FF" width="24" height="24" align="absmiddle" alt="" /> Credits & License

Created and developed by **Shreyas Landge**.

The Logic Circuit Simulator component is adapted from the open-source *Logic Simulator*. The original **MIT License** and applicable copyright notices must be retained with the reused code. Refer to the applicable license file for full terms.

---

<div align="center">

**LogicVerse: From Silicon to Code**

Developed by [Shreyas Landge](https://github.com/shreyas-landge)

[![GitHub](https://img.shields.io/badge/Explore_on-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/shreyas-landge/LogicLab)

</div>
