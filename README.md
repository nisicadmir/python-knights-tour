# The Knigh's tour

This is an app that resolves the Knigh's tour programming problem. I used Warnsdorf's rule to resolve the problem. Warnsdorf's rule is a heuristic for finding a knight's tour. The knight is moved so that it always proceeds to the square from which the knight will have the fewest onward moves.. You can find more information here: https://en.wikipedia.org/wiki/Knight%27s_tour

## Requirements: python2.7
```
git clone https://github.com/nisicadmir/python-knights-tour.git
```
```
cd python-knights-tour
```
run in terminal
```
python /path/to/the_tour.py
```

##Troubleshooting
Firstly, program will need to get input from user for N. N represents the number of x and y of chessboard. After that the chessboard is created (line 22). On lines 25 and 26 there are available moves of the Knight. The Knight will start on random positions (lines 29 and 30) but positions are not greater than N. On line 35 starts the loop. The second loop which starts on line 39 will count the available moves. If the nx and ny are negative or greater than N, the Knight will end up off the chessboard. Next loop will count the available neighbors and push it to pq. Then the program will move the knight on the field that has minimum number of available neighbors (line 56) and finally the program will print moves of the Knight.
