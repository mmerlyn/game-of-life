# 🧬 Game of Life - Visualization of Cellular Automata

This project is a simulation of **Conway's Game of Life**, built using **OpenGL in C**. It visualizes how simple rules can result in complex behavior, and we added a few enhancements like **organism aging**, color changes, and the ability for users to interact with the simulation while it runs.

## Project Goal

- A grid-based ecosystem where each cell can be alive or dead.
- The state of each cell changes in each generation based on the classic Game of Life rules.
- We added new features:
  - **Aging**: cells now die if they live too long (age > 50).
  - **Color changes**: based on age, to make it more visual.
  - **User control**: use mouse to add cells, keyboard to play/pause/reset.

## Motivation

We were fascinated by how **four simple rules** can create patterns that look alive - like gliders, guns, and colonies. Conway's Game of Life has always been an iconic example of how complexity can emerge from simplicity. So we decided to build it from scratch and add our own twist.

## 🔧 Tech Stack

- Language: **C**
- Graphics: **OpenGL + GLUT**
- IDE: **Code::Blocks**

## Features

- Random initial states
- Timed iterations with adjustable speed
- Color-coded cells based on age
- Mouse + keyboard interaction
- Smooth animation using double buffering

## Working

- Each cell has 3 properties: `alive`, `age`, and `nextState`.
- In each generation:
  - It checks its 8 neighbors.
  - Applies Conway's rules + new aging rule.
  - Updates the grid.
- Cells are drawn in real-time using OpenGL.

## Observations

- Adding an age limit reduces complexity.
- Stable "colonies" form after a few generations.
- Some patterns cycle forever unless disrupted.
- User can interact and change the outcome midway.

## System Requirements

**Hardware:**

- Core i5/i7 CPU
- 1 GB RAM
- 2 GB HDD

**Software:**

- Windows 10
- Code::Blocks IDE
- OpenGL + GLUT
- Language: C

## Future Ideas

- Let users delete cells (not just add them).
- Add different cell types (e.g. plant, predator).
- Use actual shapes instead of square pixels.
- Simulate ecosystems, not just organisms.

## Acknowledgements

This project was created as part of the **17CS68 Computer Graphics & Visualization Lab**,
6th Semester, B.E. CSE - BMS Institute of Technology & Management, Bengaluru, India

## License

This project is licensed under the [MIT License](LICENSE).

**Team Members:**

1. Aishwarya M
2. Merlyn Mercylona Maki Reddy
