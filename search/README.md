### starter files
(Starter Files)[https://inst.eecs.berkeley.edu/~cs188/fa10/projects/search/search.html#Glossary)]

python pacman.py -l tinyMaze -p SearchAgent
python pacman.py -l mediumMaze -p SearchAgent
python pacman.py -l bigMaze -z .5 -p SearchAgent

##DFS
implemented in search.py with a recursive strategy
### start
python pacman.py -p SearchAgent -a fn=depthFirstSearch

python pacman.py -l tinyMaze -p SearchAgent
python pacman.py -l mediumMaze -p SearchAgent
python pacman.py -l bigMaze -z .5 -p SearchAgent


##BFS

python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5

-Q: Does BFS find a least cost solution?


