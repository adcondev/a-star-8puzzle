# A* 8-Puzzle Solver 🧩

An efficient implementation of the A* search algorithm for solving 8-puzzle sliding tile games. Features multiple heuristics, step-by-step visualization, and performance analysis.

## Features

- 🎯 **A* Algorithm**: Optimal pathfinding implementation
- 📊 **Multiple Heuristics**: Manhattan, Euclidean, Hamming distance
- 🎨 **Visualization**: Terminal solution playback
- ⚡ **Optimizations**: Priority queue, state caching
- 📈 **Analytics**: Search statistics and performance metrics
- 🔍 **Solvability Check**: Verify puzzle can be solved

## Usage

```python
# Define initial and goal states
initial = [
    [1, 2, 3],
    [4, 0, 5],
    [7, 8, 6]
]

goal = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 0]
]
```

## Algorithm Details

The A* algorithm uses:
- **f(n) = g(n) + h(n)**
  - g(n): Cost from start to current node
  - h(n): Heuristic estimate to goal
- **Priority Queue**: For efficient node selection
- **Closed Set**: To avoid revisiting states

## Performance

- Solves most puzzles in < 100ms
- Memory efficient with state pruning
- Guaranteed optimal solution

## License

The Unlicense
