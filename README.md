# PathfindingVisualizer

This project uses Java and JavaFX to visualize pathfinding algorithms: A* and Dijkstra.

## Comparision on empty grid

| A* algorithm | Dijkstra algorithm |
| :---:      | :---:       |
| ![aalgorytm czysty](gify/aalgorytm%20czysty.gif)     | ![djikstra czysty](gify/djikstra%20czysty2.gif) |

## Maze creation(Kruskal's method and random)

| Kruskal's method | Random low/high density |
| :---: | :---: |
| ![kruskal](gify/kruskal.gif) | ![Random low density ](gify/random%20density.gif)|

## RTX ON/OFF - Real Time Experience :) - pick an algorithm
You can move start and end nodes and in the meantime it will calculate path. Turn on and pick an algorithm with a radio button.

| A* algorithm | Dijkstra algorithm |
| :---:      | :---:       |
| ![aalgorytm rtx](gify/aalgorytm%20rtx.gif)     | ![djikstra rtx](gify/djikstra%20rtx.gif) |

## Draw your own mazes
Just hold ctrl and draw walls, alt and shift to change location of start and end nodes respectively.

![draw](gify/draw.gif)

## Visited nodes and path count
Counts visited squares and path length.

## Clear
Just clears the grid.

## Change options
You can change a few options: random density, speed, grid size.

## Generate Data
Logs map(x, y, isWall, isStart, isEnd, Colour) to a file.

