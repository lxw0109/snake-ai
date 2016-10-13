# Snake AI

A snake AI written in python. Use curses module, Windows users 
should install it first:

<http://www.lfd.uci.edu/~gohlke/pythonlibs/#curses>


## How to run

	git clone https://github.com/Hawstein/snake-ai.git
	cd snake-ai
	python snake.py
	
## Demo

<img src="snake-ai.gif" />

## More in my blog

<http://hawstein.com/posts/snake-ai.html>


蛇朝着食物走，安全再走，每走一步做一次BFS；（蛇吃食物时，走最短路径）</br>
如果蛇与食物间没有路，就跟着蛇尾走，每走一步做一次BFS；（蛇跟着蛇尾走时，要走最长路径）</br>
如果蛇与食物间没有路，蛇头与蛇尾也没有路，就选一步可行的路来走，每走一步做一次BFS；</br>