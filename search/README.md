# Search

This project contains (handwritten Notes)[link to notes] from the class "SEARCH" as a part of the (AIND)[]
[https://inst.eecs.berkeley.edu/~cs188/fa10/projects/search/search.html#Glossary)] provides a pacman game, the different search algorithms 
DFS, BFS, UCS and AStar where implemented by me and can be found in search.py

## DFS
python pacman.py -p SearchAgent -a fn=depthFirstSearch
python pacman.py -l tinyMaze -p SearchAgent
python pacman.py -l mediumMaze -p SearchAgent
python pacman.py -l bigMaze -z .5 -p SearchAgent

## Breath First Search
python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5

## Uniform Cost Graph Search 
python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs
python pacman.py -l mediumDottedMaze -p StayEastSearchAgent
python pacman.py -l mediumScaryMaze -p StayWestSearchAgent
No

## A * Search
python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic 

## TODO
- implement a search with the corners problem with a corners heuristic.
- implement A*FoodSearchAgent
- implement a heuristic for the A*FoodSearchAgent

## License
This project can only be used to learning search algorithm in AI.
This project is not allowed for any business use.

