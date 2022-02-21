Simple C Program on Pointer
```c
#include<stdio.h>

int main(){
    int a=10;
    int *p;//"*" operator is used during dereferencing & declaring
    p=&a;//Initialisation can be directly done onto a pointer.
    printf("%d\n", a);//prints 10
    printf("%d\n", &a);//prints address of a
    printf("%d\n", p);//prints p which is equal to a's address
    printf("%d\n", &p);//prints address of p which equals a's address again
    printf("%d\n", *p);//prints 10
}
```

How to allocate the memory in heap?
-> Using Malloc which can be accessed in c program using the library called stdlib.h
Example:
```c
int main(){
int *p;
     p=(int *)malloc(5*sizeof(int));
}
```


How to access an array using a pointer  

```c
int main(){
    int A[5]={2,3,4,5,6}; // here the data is stored in stack/ not heap memory
    int *p;
    p=A;//how to initialising a pointer w an array
    for (int i = 0; i < 5; i++)
    {
        printf("%d", p[i]);
    }
}
```
---  
  
In order to use the heap memory
we can do this:
```c
int main(){
    int *p;
    p=(int*)malloc(5*sizeof(int));
    p[0]=1;p[1]=2;p[2]=3;p[3]=4;p[4]=5;
    
    for (int i = 0; i < 5; i++)
    {
        printf("%d", p[i]);
    }
    

}
```
