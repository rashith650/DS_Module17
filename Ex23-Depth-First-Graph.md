# Ex23 Depth First Graph
## DATE: 27/05/2025
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1. Start
2. Allocate memory for a new node.
3. Set the vertex field of the new node to the given value v.
4. Set the next pointer of the new node to NULL.
5. Return the newly created node.
6. End
   

## Program:
```
/*
Program to traverse the graph below in the depth first fashion

*/
struct node* createNode(int v) {
    struct node* newNode=malloc(sizeof(struct node));
    newNode->vertex=v;
    newNode->next=NULL;
    return newNode;
```

## Output:

![image](https://github.com/user-attachments/assets/b51c7114-53e3-4311-896e-23dbd4825a6e)



## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
