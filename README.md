# Udacity Nanodegree: Flying Car and Autonomous Flight Engineer

This project contains working code, notes and ideas of this nanodegree.

## 2. Planning

### 2.1. Planning as Search

- A-Start Search
- 3D Motion Planning
- Perfect solution <> Reasonable solution in reasonable time
- Continuous --> Discrete state
- Define Planning Problem & Search Space:

  - All Possible States
  - Start State
  - Goal State
  - Actions
  - Costs

- Discretization: Grid representation

- A partial plan:

  - doesn't need to be a good plan, and doesn't reach the goal
  - does constitute a valid list of states and actions the vehicle could take from the start state.

- Breadth vs Depth:

- Breadth-First Search:

  - always expands shortest plan first
  - finds the shortest path to goal first
  - can be computationally intensive

- Depth-First Search:
  - expands last successful action
  - require luck
  - can fail completely
