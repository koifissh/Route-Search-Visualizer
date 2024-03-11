
<p float="center">
  <p align="center"><img src="https://github.com/koifissh/Route-Search-Visualizer/assets/112574689/9695d5cd-548a-4db8-9cb8-2ebbe4f30299" width="620" />
</p>

## Route Search Algorithm Visualizer
Author: Daniel Huynh

## Statement
This information can be used to visualize and develop several searching algorithms in order to comprehend how they navigate in a graph with specific adjacencies and costs in mind. In this graph, coordinates of towns in Kansas were provided along with adjacencies each town may have with one another. The cost is based on distances from each town.
1. Search Algorithms Involved:
  -  Breadth-First Search
  -  Depth-First Search
  -  Iterative Deepening Depth-Search
  -  A* Search

## Usage
To use this program, follow these steps:

1. Ensure that you have the necessary CSV and python files
2. Adjust the filepath for `Adjacencies.txt` and `coordinates.csv` accordingly
3. Run the `SearchVisualizer.ipynb` file.
4. The program will show you a list of cities available to select
   -   Start City: The source node from which the algorithm selected will start at
   -   Goal City: The goal node from which the algorithm will attempt to reach
5. Algorithms to be selected from 1-6 number input
   -  Search Algorithms Involved:
   -  Breadth-First Search
   -  Depth-First Search
   -  Iterative Deepening Depth-Search
   -  A* Search
<p align="center"><img width="200" alt="Screenshot 2024-03-11 at 3 23 11 AM" src="https://github.com/koifissh/Route-Search-Visualizer/assets/112574689/a74744ea-8c50-42ee-8464-a8b6f7c001e3">

7. At the end, The program will provide a visual map of the route taken, route taken, total distance traveled, and the execution time of the algorithm selected
<p align="center"><img width="788" alt="Screenshot 2024-03-11 at 3 31 11 AM" src="https://github.com/koifissh/Route-Search-Visualizer/assets/112574689/8ccec3bc-5aca-44fa-b30c-ad7f12309402">

## Additional Details
- The program can be ran multiple times to select and test different cities and algorithms

## Limits
- Time limit didn't allow for a more accurate cost calculation for edges that connect the nodes together.
