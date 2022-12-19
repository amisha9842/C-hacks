# C-hacks
int * p #pointer 'p' is going to store address of a node with int datatype

node in a linked list= data part+link part(the one storing address of next node.


struct node *next  # 'next' pointer will be storing address of data part of the node with datatype 'struct node'(it is a user defined datatype)

In linked list,random access is not possible.

best case scenario in linked list for traversing the list is O(1)
worst case scenario for the same will be O(n).(when last element in the list is to be displayed)

binary search is not possible in a linked list coz we cannot reach the middle element of the list directly.

singly linked list:
{


only forward traversal possible
struct node

{
int data;
struct node *next;
};

doubly linked list:
{

contains data part and two pointers.

both forward and backwards traversal possible.

struct node

{

int data;

struct node *next;

struct node *prev;

};

circular linked list: each element is having a link to its next element while the pointer attached to the last element stores the address of the first element.

doubly circular linked list: the prev pointer of the first element stores the address of the last element of the list while the 'next' pointer of the last element stores the address of the first element of the list.

//for traversal:
array take O(1) for accessing any element of the array

linked list takes O(n)

//memory requirement in linked list >memory requirement in an array(since along withe the element,address of next node in the form of pointer datatye needs also to be stored).

//memory utilisation is efficient in linked list and not in array.

//implementation of linked list

head pointer stores the address of 1st node

#creating a node
struct node

{

int data;

struct node *next;

};

struct node *head, *newnode;

head=0;

newnode=(struct node *)malloc(sizeof(struct node))

 
