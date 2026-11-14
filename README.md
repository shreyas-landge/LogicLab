::: {align="center"}
# LogicVerse

### From Silicon to Code --- An Interactive Digital Electronics Learning Platform

[![Project](https://img.shields.io/badge/Project-LogicVerse-6C63FF?style=for-the-badge&logo=github)](https://github.com/shreyas-landge/LogicLab)
[![Course](https://img.shields.io/badge/Course-FOIDS-0A7B83?style=for-the-badge)](#-academic-information)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**Explore digital electronics through interactive visual simulations.**

[<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/rocket.svg" width="18" height="18" alt="Getting started" /> Explore Repository](https://github.com/shreyas-landge/LogicLab) ·
[Project Structure](#-project-structure) · [🛠️ Getting
Started](#-getting-started) · [License](#-credits-and-license)
:::<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/compass.svg" width="18" height="18" alt="Navigation" /> Quick Navigation
<details open>
<summary>
<strong>{=html}Click to expand or collapse the
contents`</strong>`{=html}
</summary>
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/search.svg" width="18" height="18" alt="Overview" /> Project Overview
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/sparkles.svg" width="18" height="18" alt="Features" /> Features
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/layers.svg" width="18" height="18" alt="Layers" /> Six Learning Layers
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/target.svg" width="18" height="18" alt="Objectives" /> Project Objectives
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/wrench.svg" width="18" height="18" alt="Technology" /> Technology Stack
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/folder-tree.svg" width="18" height="18" alt="Structure" /> Project Structure
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/rocket.svg" width="18" height="18" alt="Getting started" /> Getting Started
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/flask-conical.svg" width="18" height="18" alt="Learning outcomes" /> Learning Outcomes
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/map.svg" width="18" height="18" alt="Future enhancements" /> Future Enhancements
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/graduation-cap.svg" width="18" height="18" alt="Academic information" /> Academic Information
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/award.svg" width="18" height="18" alt="Credits" /> Credits and License
</details>
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/search.svg" width="18" height="18" alt="Overview" /> Project Overview
LogicVerse is an interactive digital electronics learning platform
developed as part of the Foundations of Intelligent Digital Systems
(FOIDS) course.

It brings together two complementary learning environments:
  Module                  What it covers          Open locally
  <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/puzzle.svg" width="18" height="18" alt="Logic simulator" /> Logic Circuit      Logic circuits, Boolean [`logic-simulator/index.html`](logic-simulator/index.html)
Simulator             expressions, logic
operations and K-map
tools                   
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/monitor.svg" width="18" height="18" alt="Computer" /> Full Digital       A learning journey from [`full-simulator/index.html`](full-simulator/index.html)
Electronics Simulator semiconductor physics
to CPU execution
The aim is to make abstract digital-electronics concepts easier to
explore through visual and interactive demonstrations.
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/sparkles.svg" width="18" height="18" alt="Features" /> Features
<details open>
<summary>
<strong>{=html}<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/puzzle.svg" width="18" height="18" alt="Logic simulator" /> Logic Circuit Simulator`</strong>`{=html}
</summary>
- Interactive logic-circuit workspace.
- Boolean-expression analysis.
- Logic-gate operations.
- Truth-table tools.
- Boolean-expression simplification.
- Karnaugh map (K-map) minimization.
- Visual representation of digital logic.
</details>
<details>
<summary>
<strong>{=html}<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/monitor.svg" width="18" height="18" alt="Computer" /> Full Digital Electronics Simulator`</strong>`{=html}
</summary>
- Six connected learning layers.
- Visual exploration of concepts from semiconductor physics to
  instruction execution.
- Separate modules for each layer.
- Browser-based interface.
</details>
Note: The exact availability of individual controls depends on the
current implementation in the repository. Check each simulator before
treating every listed capability as complete.

<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/layers.svg" width="18" height="18" alt="Layers" /> Six Learning Layers
The Full Digital Electronics Simulator is organized into six layers:
```mermaid
flowchart TD
    A["<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/atom.svg" width="18" height="18" alt="Semiconductor physics" /> Layer 1<br/>Semiconductor Physics"] --> B["<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/cable.svg" width="18" height="18" alt="Transistors" /> Layer 2<br/>Transistors"]
    B --> C["<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/circuit-board.svg" width="18" height="18" alt="Logic gates" /> Layer 3<br/>Logic Gates"]
    C --> D["<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/puzzle.svg" width="18" height="18" alt="Logic simulator" /> Layer 4<br/>Digital Circuits"]
    D --> E["<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/monitor.svg" width="18" height="18" alt="Computer" /> Layer 5<br/>CPU Architecture"]
    E --> F["<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/cog.svg" width="18" height="18" alt="Execution" /> Layer 6<br/>Instruction Execution"]
```
  Layer   Topic                      Learning focus
  1       <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/atom.svg" width="18" height="18" alt="Semiconductor physics" /> Semiconductor Physics   Foundations of semiconductor devices
2       <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/cable.svg" width="18" height="18" alt="Transistors" /> Transistors             Transistors as electronic switches
3       <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/circuit-board.svg" width="18" height="18" alt="Logic gates" /> Logic Gates             Basic digital gates and their operations
4       <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/puzzle.svg" width="18" height="18" alt="Logic simulator" /> Digital Circuits        Combining gates into digital circuits
5       <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/monitor.svg" width="18" height="18" alt="Computer" /> CPU Architecture        Fundamental CPU components
6       <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/cog.svg" width="18" height="18" alt="Execution" /> Execution               How instructions are processed and executed
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/target.svg" width="18" height="18" alt="Objectives" /> Project Objectives
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/book-open.svg" width="18" height="18" alt="Learning" /> Understand the fundamentals of digital electronics.
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/atom.svg" width="18" height="18" alt="Semiconductor physics" /> Explore how semiconductor devices form the foundation of digital
  systems.
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/cable.svg" width="18" height="18" alt="Transistors" /> Understand transistor switching.
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/circuit-board.svg" width="18" height="18" alt="Logic gates" /> Learn the operation of logic gates.
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/calculator.svg" width="18" height="18" alt="Boolean algebra" /> Explore Boolean algebra and logic-circuit design.
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/brain.svg" width="18" height="18" alt="Digital systems" /> Connect individual gates to larger digital systems.
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/monitor.svg" width="18" height="18" alt="Computer" /> Understand basic CPU architecture and instruction execution.
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/flask-conical.svg" width="18" height="18" alt="Learning outcomes" /> Support learning through visual demonstrations.
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/wrench.svg" width="18" height="18" alt="Technology" /> Technology Stack
::: {align="center"}
[![HTML5](https://skillicons.dev/icons?i=html)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://skillicons.dev/icons?i=css)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://skillicons.dev/icons?i=js)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Git](https://skillicons.dev/icons?i=git)](https://git-scm.com/)
[![GitHub](https://skillicons.dev/icons?i=github)](https://github.com/)
:::  Technology   Role
  HTML5        Page structure
CSS3         Styling and layout
JavaScript   Interactive behavior and simulation logic
Git          Version control
GitHub       Source-code hosting
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/folder-tree.svg" width="18" height="18" alt="Structure" /> Project Structure
<details>
<summary>
<strong>{=html}Show repository tree`</strong>`{=html}
</summary>
LogicLab/
│
├── index.html
├── README.md
│
├── logic-simulator/
│   ├── index.html
│   ├── app.js
│   ├── circuit.js
│   ├── logic.js
│   ├── kmap.js
│   ├── style.css
│   └── README.md
│
└── full-simulator/
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
</details>
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/rocket.svg" width="18" height="18" alt="Getting started" /> Getting Started
Requirements
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/globe.svg" width="18" height="18" alt="Browser" /> A modern web browser: Chrome, Firefox, Edge or Safari.
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/code.svg" width="18" height="18" alt="Developer tools" /> Git (optional, for cloning).
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/puzzle.svg" width="18" height="18" alt="Logic simulator" /> VS Code with Live Server (optional).
1. Clone the repository
git clone https://github.com/shreyas-landge/LogicLab.git
2. Enter the project directory
cd LogicLab
3. Run the project
Open the root index.html file in your browser.

Alternatively, open the project in VS Code and use the Live Server
extension.
4. Open a simulator directly
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/puzzle.svg" width="18" height="18" alt="Logic simulator" /> Logic Circuit Simulator: logic-simulator/index.html
- <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/monitor.svg" width="18" height="18" alt="Computer" /> Full Digital Electronics Simulator: full-simulator/index.html
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/flask-conical.svg" width="18" height="18" alt="Learning outcomes" /> Learning Outcomes
By exploring the relevant implemented modules, learners can study:
- Semiconductor fundamentals.
- Transistor switching.
- Basic and derived logic gates.
- Boolean algebra.
- Truth tables.
- Sum of Products (SOP) and Product of Sums (POS).
- Minterms and maxterms.
- Karnaugh map simplification.
- Combinational digital circuits.
- Basic CPU architecture.
- Instruction-execution concepts.
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/map.svg" width="18" height="18" alt="Future enhancements" /> Future Enhancements
- [ ] Add sequential-circuit simulations.
- [ ] Add flip-flops and registers.
- [ ] Introduce counters and shift registers.
- [ ] Expand CPU architecture demonstrations.
- [ ] Add guided experiments and practice exercises.
- [ ] Improve simulation controls and visual explanations.
- [ ] Add more interactive circuit components.
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/graduation-cap.svg" width="18" height="18" alt="Academic information" /> Academic Information
  Field             Details
  Project       LogicVerse --- Interactive Digital Electronics Simulator
Developer     Shreyas Landge
Subject       Foundations of Intelligent Digital Systems (FOIDS)
Program       B.Tech --- Artificial Intelligence and Data Science
Institution   Vishwakarma Institute of Technology, Pune
<img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/award.svg" width="18" height="18" alt="Credits" /> Credits and License
Created and developed by Shreyas Landge.

The Logic Circuit Simulator component is adapted from the open-source
Logic Simulator.

The original MIT License and applicable copyright notices must be
retained with the reused code. Refer to the applicable license file for
licensing terms.
::: {align="center"}
### LogicVerse --- From Silicon to Code

**Developed by Shreyas Landge**

[![GitHub](https://img.shields.io/badge/Explore_on-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/shreyas-landge/LogicLab)
:::