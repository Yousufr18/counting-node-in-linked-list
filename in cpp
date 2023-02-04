#include<iostream>
using namespace std;
struct node{
    int data;
    struct node *next;
};
struct node *head=NULL;
void insert(int newdata){
    struct node *newnode=(struct node *)malloc(sizeof(struct node));
    newnode->data=newdata;
    newnode->next=head;
    head=newnode;
}
void count(struct node *head){
    int count=0;
    if(head==NULL)
    {
        cout<<"NO LIST";
    }
    struct node *ptr=NULL;
    ptr=head;
    while(ptr!=NULL)
    {
        count++;
        ptr=ptr->next;
    }
    cout<<count;
}

int main()
{
    insert(3);
    insert(4);
    insert(5);
    count(head);
    
}
