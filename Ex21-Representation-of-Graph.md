# Ex21 Representation of Graph
## DATE:
## AIM:
To write a C program to display the adjacency matrix of the given graph by supplying the edges and the number of vertices.

## Algorithm
1. Start
2. Read the value of V (number of vertices).
3. Declare an adjacency matrix adjMatrix[V][V].
4. Initialize the matrix to 0 using the init function. 
5. Calculate the maximum number of edges me as n * (n - 1) / 2.  

## Program:
```
/*
Program to display the adjacency matrix of the given graph
Developed by: GANESH PRABHU J 
RegisterNumber: 212223220023

#include<stdio.h> int V;

//init matrix to 0 voidinit(int arr[][V])
{
int i,j;
for(i = 0; i < V; i++) for(j= 0; j< V; j++)
arr[i][j] = 0;
}
*/
int main()
{ int e1,e2,me,n,i;
scanf("%d",&V); int adjMatrix[V][V]; init(adjMatrix); n=V;
 
me=n*(n-1)/2; for(i=0;i<me;i++)
{
scanf("%d%d",&e1,&e2); addEdge(adjMatrix,e1,e2); if(e1==-1 && e2==-1)
{
break;
}
}
printAdjMatrix(adjMatrix);
}
```

## Output:

<img width="537" height="352" alt="439811784-6f5dccf8-b924-4587-ad10-f8665c38055a" src="https://github.com/user-attachments/assets/73f94374-bece-487d-9404-60a254f0fc69" />


## Result:
Thus, the C program to print the adjacency matrix of the given graph is implemented successfully.
