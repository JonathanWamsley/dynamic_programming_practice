# Dynamic Programming practice

I am learning Dynamic programming through Andrey Grehov Dynamic programming series. His [Youtube series](https://www.youtube.com/watch?v=KTDwvph8Tzo&list=PLVrpF4r7WIhTT1hJqZmjP10nxsmrbRvlf&index=3)and [Git repo](https://github.com/andreygrehov/dp/tree/master/lecture6)

I am adapting the code from Golang to Python.

I am also creating a project to go over some dp concepts.

# Project 1: Finding the best path for Mario to get to Bowsers castle

    Problem: Mario needs to get to bowsers castle
    Mario can move forward by doing a walking, jogging, or running [1, 2, 3] movement speed
    He must avoid the obstacles and collect the coins along the path
    The path has a time constraint added by p = [-n, -(n-1), -(n-2), ... -3, -2, -1, 0]
    This will make mario prefer to take 3 jumps if there are no traps or coins.
    If there is a coin, the cell block becomes + n*10
    If there is a trap, the cell block becomes - n*10
    
    Help Mario find the best score/path to bowsers castle