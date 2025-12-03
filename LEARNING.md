# Learning: A* 8-Puzzle Solver

## Project Overview
This project is a Python-based implementation of an Artificial Intelligence solver for the classic 8-puzzle game. It utilizes the **A* (A-Star) search algorithm** to find the optimal solution path from a scrambled initial state to a target configuration. The core objective was to understand and implement heuristic search strategies and manage state space exploration efficiently.

## Tech Stack and Key Technologies
- **Language**: Python 3
- **Core Concepts**: Artificial Intelligence, Search Algorithms, Heuristics, Object-Oriented Programming (OOP)

## Notable Libraries
- **Standard Library**: The project relies entirely on Python's standard library, demonstrating a "from scratch" implementation of data structures and algorithms without external dependencies.

## Major Achievements and Skills Demonstrated
- **Algorithm Implementation**: Successfully implemented the A* search algorithm from scratch, including the core logic for `f(n) = g(n) + h(n)`.
- **Heuristic Design**: Implemented a heuristic function based on the **Hamming distance** (number of misplaced tiles) combined with depth cost to guide the search.
- **Custom Data Structures**: Designed and implemented a custom **Priority Queue** (`BestFirst` class) to efficiently manage the "open set" of states, ensuring the most promising nodes are explored first.
- **State Management**: Developed a robust state representation (`Nodo` class) that tracks the puzzle configuration, parent state, movement history, and path cost.
- **Optimization**: Implemented cycle detection and duplicate state handling using a "closed set" (`ColaQ` class) to prevent infinite loops and redundant processing.

## Skills Gained/Reinforced
- **Artificial Intelligence**: Deepened understanding of informed search strategies and heuristic functions.
- **Algorithm Design**: Reinforced skills in designing and debugging complex recursive/iterative algorithms.
- **Data Structures**: Practical experience with Priority Queues, Trees (implicitly formed by parent pointers), and Hash/Set-based lookups for visited states.
- **Python OOP**: Enhanced object-oriented design skills by modeling the problem domain with cohesive classes (`Nodo`, `ColaQ`, `BestFirst`).
