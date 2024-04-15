# DFS-Parallelization
In the given implementation we define the number of threads for the DFS Algorithm using the number of children or branches the source node has in the Directed Acyclic Graph (DAG) in this implementation. The higher the number of children the more the paralleism of the Depth First Search yeilding better performances for the algorithm *(The DFS here is implemented using stacks for dealing with shared variables more easily)*.

## How to Run
***(Note: First Ensure you have C/C++ Compiler in your system along with the OpenMP Environment to run the code)***

You can run the following algorithm using the commands as shown in your terminal:
```
> g++ -fopenmp parallelDFS.cpp -o run.exe
> ./run.exe
```

