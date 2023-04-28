#include<stdio.h>
#define CAPACITY 3
int stack[CAPACITY];
int top=-1;// no value
void push(int x){
 if(top<CAPACITY-1){
 top=top+1;
 stack[top]=x;
 printf("Successsfully added item:%d\n",x);
}  
   else{
       printf("Exception! no Spaces.\n");
   } 
}



int pop(){
     
if(top>=0){
    
    
    int val=stack[top];
    top=top-1;
    return val;
}
     printf("Exception from pop! Empty stack");
    return -1;
    
}

int peek(){
    if(top>=0){
        return stack[top];
    }
    printf("Exception from peek! Empty stack\n");
  return -1;  
    
}















int main(){
    
    
   printf("Implementation my stack in c.\n") ;

   peek();
    push(10);
    push(20);
    push(30);
    printf("pop item:%d\n",pop());
    push(40);
    printf("Top of the stack:%d\n",peek());
    return 0;
}#include<stdio.h>
#define CAPACITY 3
int stack[CAPACITY];
int top=-1;// no value
void push(int x){
 if(top<CAPACITY-1){
 top=top+1;
 stack[top]=x;
 printf("Successsfully added item:%d\n",x);
}  
   else{
       printf("Exception! no Spaces.\n");
   } 
}



int pop(){
     
if(top>=0){
    
    
    int val=stack[top];
    top=top-1;
    return val;
}
     printf("Exception from pop! Empty stack");
    return -1;
    
}

int peek(){
    if(top>=0){
        return stack[top];
    }
    printf("Exception from peek! Empty stack\n");
  return -1;  
    
}

int main(){
    
    
   printf("Implementation my stack in c.\n") ;

   peek();
    push(10);
    push(20);
    push(30);
    printf("pop item:%d\n",pop());
    push(40);
    printf("Top of the stack:%d\n",peek());
    return 0;
}
