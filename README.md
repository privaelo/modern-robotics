# modern_robotics

My working through Kevin Lynch's *Modern Robotics* specialization (Northwestern University, Coursera) — a six-course graduate-level program in robot mechanics, planning, and control. This repo collects assignment results, short demos, and visualizations per module as I progress through the specialization.

<!-- TODO: add hero demo GIF of the current completed course -->

## What this is

A public log of my work through the specialization. For each course, I publish: assignment results, short demos of concepts in motion, and visualizations that make the math concrete.

## Scope

- **6 courses**: foundations, kinematics, dynamics, motion planning and control, manipulation and mobile robots, and a mobile-manipulation capstone
- **Assignment results** — outputs from graded Coursera assignments
- **Demos** — short videos or GIFs of key concepts (e.g., robot arm forward kinematics, trajectory generation, feedback control)
- **Visualizations** — plots and diagrams that illustrate the mechanics

## Status

Currently working through **Course 1: Foundations of Robot Motion**.

## Roadmap

One section per course. Each course gets its own subdirectory with assignment outputs, demos, and a short write-up of what was covered.

| Course | Title | Textbook Chapters | Status |
| ------ | ----- | ----------------- | ------ |
| 1 | Foundations of Robot Motion | 2, 3 | ⏳ In progress |
| 2 | Robot Kinematics | 4, 5, 6, 7 | ⬜ Planned |
| 3 | Robot Dynamics | 8, 9 | ⬜ Planned |
| 4 | Robot Motion Planning and Control | 10, 11 | ⬜ Planned |
| 5 | Robot Manipulation and Wheeled Mobile Robots | 12, 13 | ⬜ Planned |
| 6 | Capstone — Mobile Manipulation | — | ⬜ Planned |

## Stack

- Python 3.10+
- [`ModernRobotics`](https://github.com/NxRLab/ModernRobotics) — the official companion library
- NumPy, Matplotlib for computation and plotting
- Jupyter for local exploration

## Running the demos

Requires Python 3.10+.

```bash
python -m venv .venv
source .venv/bin/activate     # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Each course subdirectory has its own README with instructions for reproducing its demos.

## References

- Lynch, K. M., & Park, F. C. (2017). *Modern Robotics: Mechanics, Planning, and Control*. Cambridge University Press. [modernrobotics.org](http://modernrobotics.org)
- [Modern Robotics Specialization on Coursera](https://www.coursera.org/specializations/modernrobotics) — Northwestern University
- [`modern_robotics`](https://github.com/NxRLab/ModernRobotics) — official companion Python library