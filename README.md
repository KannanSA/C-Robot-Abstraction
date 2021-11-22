# Robot Abstraction

This C program is Robot Abstraction made by Kannan Sekar Annu Radha

## Run

Use gcc to compile main.c (gcc -o main main.c graphics.c) then use (./main | java -jar drawapp.jar)

```bash
gcc -o main main.c graphics.c  
```
```bash
./main | java -jar drawapp.jar 
```

![Robot](/robot.png)
## Markers and Blockers

Markers are grey
Blockers are red

![Robot1](/robot1.png)

## Functions in main
    zigzag(); is a search algorithm that hugs the walls
    rightloop(); is an algorithm that keeps turning right
    solution(); is code that goes to the marker

    To change position of robot go to main and change roboX and roboY and *direction to one of 'R' = right, 'L' = left, 'D' = down, 'U' = up
