# EX 58 C Function to display queue elements using Linked List.(use double data in the queue)
## DATE: 17.11.2025
## AIM:
To write a C Function to display queue elements using Linked List.

## Algorithm
1.Start.
2.Define a structure Node with fields float data and pointer next.
3.Initialize front = NULL and rear = NULL.
4.Check if front == NULL; if true, print "Queue is empty" and exit.
5.Assign temp = front.
6.Traverse while temp != NULL and print temp->data.
7.Move temp = temp->next.
8.Repeat until temp == NULL.
9.End. 

## Program:
```
/*
C Function to display queue elements using Linked List.(use double data in the queue)

Developed by: Aparna RB
RegisterNumber: 212222220005
struct Node
{
   float data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void display()
{
    struct Node *ptr=front;
    if(ptr==NULL)
    {
        printf("queue is empty\n");
    }
    
    else
    {
    printf("Queue elements:");
    while(ptr!=NULL)
    {
    printf("\n%.3f",ptr->data);
    ptr=ptr->next;
    }
}
} 
*/
```

## Output:


<img width="761" height="610" alt="image" src="https://github.com/user-attachments/assets/d13095af-d389-4d9d-bcfd-77317e20f233" />

## Result:
Thus the program was executed and the output was verified successfully.
