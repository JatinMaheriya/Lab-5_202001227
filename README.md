Name : Maheriya Jatin B.
Student ID : 202001227
Lab : 5


File 1 :-

 https://github.com/OmkarPathak/Data-Structures-using-Python/blob/master/Graph/P01_BreadthFirstSearch.py

Output :-

![image](https://user-images.githubusercontent.com/82827719/225572896-61e54d26-372e-48ca-b83e-1a06e134e1c7.png)

File 2 :-

https://github.com/OmkarPathak/Data-Structures-using-Python/blob/master/Graph/P02_DepthFirstSearch.py

Output :-

![image](https://user-images.githubusercontent.com/82827719/225573610-c120eacf-7e60-4aa9-a208-4b703695845e.png)



Understanding :

1) Module name "202001227_Q1" doesn't conform to snake_case naming style (invalid-name) 
--> This Means this file is not following the snake case naming style.

2) Missing class docstring (missing-class-docstring)
--> Used when a function or method has no docstring. Some special methods like __init__ do not require a docstring.

3) Consider iterating the dictionary directly instead of calling .keys() (consider-iterating-dictionary)
--> This means we can iterate dictionary directly.

4)  Comparison 'visited[i] == False' should be 'visited[i] is False' if checking for the singleton value False, or 'not visited[i]' if testing for falsiness (singleton-comparison)
--> This is telling that for checking visited[i] == false we should use 'visited[i] is False' for the singleton value False.

