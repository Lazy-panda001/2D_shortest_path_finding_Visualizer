# Shortest-path-2D

**GIF**
![WhatsApp Video 2020-12-19 at 5 32 27 PM](https://user-images.githubusercontent.com/30202180/102689291-f2842580-4222-11eb-845f-e498a57fb349.gif)
![WhatsApp Video 2020-12-19 at 5 36 30 PM](https://user-images.githubusercontent.com/30202180/102689297-f617ac80-4222-11eb-9e7e-54350cf28538.gif)





1. **Color coding** :
	1. Unexplored cells ->White
	2. Blocked cells -> Black
	3. Start cell -> Blue
	4. End cell -> Red 
	5. Explored cells -> Pink
	6. Shortest Path by Dijkstra  -> Green
	7. Shortest Path by A-star  ->  Yellow
	8. Green button(PathD-1)-> Dijkstra
	9. Red button(PathA-2)-> A*
	10. Distance-1 : Dijkstra path length 
	11. Distance-2 : A* path length
	11. The horizontal and vertical movement cost -> 1
	12. Diagonal cost -> √2.


2. **Major components** :
	1. Main loop 
	2. Dijkstra program
	3. A*

3. **Implementation** :
	1. Map as 2D array of cells
	2. Binary representation of cells as 0 and 1 for blocked and open cells
	3. Each cell has information of its parent and its state of exploration


4. **## Build For Linux user ##**
	1. **Download the zip file then unzip at the location 'Home'**:
		1. `cd Shortest-path-2D-main` 
	2. **Install sfml**: `sudo apt-get install libsfml-dev`
	3. **Complile path.cpp** :
		1. `g++ main.cpp -std=c++11 -lsfml-window -lsfml-system -lsfml-graphics`
	4. **Run the exectuable** : `./a.out`

3. **Supported operations:**
	1.  You can left click on blocks to draw black walls on the grid.
	2.  Search using either Dijkstra or A* pathdinging algorithm by clicking the respective buttons.
