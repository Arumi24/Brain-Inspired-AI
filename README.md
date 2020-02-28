# Brain-Inspired-AI

**_Jupyter Notebook_** for Brain Inspired Artificial Intelligent 

## B.py

Programmed an **_AI_** to help solve classical game **_8-Puzzle_**. I programmed **_4 Classes_**, a **_Node_** class, **_Tree_** class, **_Board_** class, and a **_PuzzleSolver_** class, I use my **_Tree Data Structure_** with given **_Nodes_** as states of the board to **_branch out_** all possible configurations of moves the board allows until the goal is reached using **_breadth first search_** but with some added components... I use methods to help **_optimize time complexity_** such as **_memoization_** so that the same board states would not get recalculated and I added a **_heuristic_** to help make my search faster, thus making my algorithm **_""Intelligent""_**, I also added a **_timer_** where you can see the time difference when using the heuristic vs when not using it, and adding the **_heuristic_** definately helps improve performance
