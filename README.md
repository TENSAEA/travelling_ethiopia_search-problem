# Traveling Ethiopia Search Problem

**Author**: Tensae Aschalew GSR/3976/17

## Description

This project addresses the Traveling Ethiopia search problem using various search algorithms. The goal is to find optimal paths between different locations in Ethiopia based on given state space graphs.

## Algorithms Implemented

- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Uniform Cost Search (UCS)
- A\* Search
- MiniMax Search

## Usage Instructions

To run the project, open the Jupyter notebook `traveling_ethiopia_search_problem.ipynb` and execute the cells sequentially. Ensure you have the necessary libraries installed.

## Results

- **Question 1**: Successfully converted Figure 1 to a Dictionary.
  - BFS Path: ['Kartum', 'Tumer', 'Shire', 'Axum', 'Adigrat', 'Mekele', 'Alamata', 'Dessie', 'Debre Sina', 'Addis Ababa', 'Bishoftu', 'Batu', 'Assassa', 'Dodola', 'Bale', 'Liben', 'Moyale']
  - DFS Path: ['Kartum', 'Tumer', 'Shire', 'Debark', 'Gondar', 'Azazo', 'Metekel', 'Bahir Dar', 'Debre Markos', 'Finote Selam', 'Ambo', 'Nekemte', 'Gimbi', 'Gambella', 'Bonga', 'Jimma', 'Hossana', 'Shashemene', 'Hawassa', 'Dilla', 'Yabello', 'Konso', 'Moyale']
- **Question 2**: Successfully converted Figure 2 to a Dictionary.

  - UCS Path: ['Addis Ababa', 'Debre Sina', 'Dessie', 'Lalibela']

- **Question 3**: Successfully converted Figure 3 to a Dictionary.

  - A\* Path: ['Addis Ababa', 'Bishoftu', 'Batu', 'Assassa', 'Shashemene', 'Hawassa', 'Dilla', 'Yabello', 'Konso', 'Moyale']

- **Question 4**: Successfully converted Figure 4 to a Dictionary.
  - Best achievable utility value for the coffee: 5
  - Best Path: ['Addis Ababa', 'Ambo', 'Gedo', 'Finca']

## Figures

- Figure 1: Traveling Ethiopia (State Space Graph)
- Figure 2: Traveling Ethiopia (Backward Cost Graph)
- Figure 3: Traveling Ethiopia (Heuristic and Backward Cost Graph)
- Figure 4: Adversary Traveling Ethiopia

#The End
