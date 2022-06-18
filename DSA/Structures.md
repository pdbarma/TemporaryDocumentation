Basic Structure c program
```c
#include<stdio.h>

struct rectangle{
    int lenght;//2 byte
    int breadth;//2 byte
};//total 4 byte for rectangle

int main(){
    //struct rectangle r;//(Variable r rectangle declaration)
    struct rectangle r={10,5};//initialisation for rectangle r with lenght & breadth of 10,5 respectively
    r.lenght =15;//assigning new data while using the dot "." operator to access the structure rectangle
    r.breadth = 5;
    printf("Area of rectangle is %d", r.lenght*r.breadth);
}
```

```c
#include<stdio.h>
#include<string.h>

struct student{
    char name[30];
    int roll;
    char address[100];
    //we can add more data in our structure
};

int main()
{
    struct student s1,s2;
    strcpy(s1.name,"SAM");
    s1.roll=1999; 
    strcpy(s1.address,"Hello there Welcome to my home");
    strcpy(s2.name,"MONALISA");
    s2.roll=2000;
    strcpy(s2.address,"Hello there Welcome to my home");//strcpy() it will leave source unchanged, but target is modified
    printf("%s ; %d ; %s", s1.name,s1.roll, s1.address);
    printf("%s ; %d ; %s", s2.name,s2.roll, s2.address);

}
```
Note use strcpy for accepting strings character in c language. dunno dont ask me the compiler didnt accept direct input
