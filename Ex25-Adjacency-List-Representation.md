# Ex25 Adjacency List Representation
## DATE:
## AIM:
To write a C program to represent the given graph using the adjacency list.

## Algorithm
1.Read the number of vertices and number of edges.

2.Read all edge pairs (source and destination) and store them.

3.Create a graph using the input edge list.

4.Print the adjacency list representation of the graph.

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: GANESH PRABHU J
RegisterNumber: 212223220023  
*/
int main(void)
{ int n,i; scanf("%d",&N);
scanf("%d",&n);
// input array containing edges of the graph (as per the above diagram)
// (x, y) pair in the arrayrepresents an edge fromx to y struct Edge edges[n];
for (i = 0; i < n; i++)
{
// get the source and destination vertex scanf("%d",&edges[i].src);
scanf("%d",&edges[i].dest);

}

// construct a graph from the given edges struct Graph*graph= createGraph(edges, n);
// Function to print adjacency list representation of a graph printGraph(graph);
return 0;
}
```

## Output:

<img width="676" height="773" alt="439813933-b06027a3-b693-427c-be16-99e921cd69f5" src="https://github.com/user-attachments/assets/d36cb34b-f015-44c3-872f-90f442d9b323" />


## Result:
Thus, the C program to represent the given graph using the adjacency list is implemented successfully
