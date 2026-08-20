Day 1 - Introduction to C 
Day 2 - Structure of a C Program
Day 3 - Variables and Constants
Day 4 - Data Types
Day 5 - Input and Output
Day 6 - Operators
Day 7 - Arithmetic Operators
Day 8 - Relational Operators
Day 9 - Logical Operators
Day 10 - Assignment Operators
Day 11 - Increment and Decrement Operators
Day 12 - Conditional Operator
Day 13 - Type Casting
Day 14 - If Statement
Day 15 - If-Else Statement
Day 16 - Nested If-Else
Day 17 - Else-If Ladder
Day 18 - Switch Statement
Day 19 - For Loop
Day 20 - While Loop
Day 21 - Do-While Loop
Day 22 - Break Statement
Day 23 - Continue Statement
Day 24 - Nested Loops
Day 25 - Pattern Printing
Day 26 - Number Patterns
Day 27 - Star Patterns
Day 28 - Functions Introduction
Day 29 - Function Parameters
Day 30 - Return Values
Day 31 - Call by Value
Day 32 - Recursion
Day 33 - Arrays Introduction
Day 34 - One-Dimensional Arrays
Day 35 - Array Operations
Day 36 - Searching in Arrays
Day 37 - Linear Search
Day 38 - Sorting Arrays
Day 39 - Bubble Sort
Day 40 - Selection Sort
Day 41 - Insertion Sort
Day 42 - Two-Dimensional Arrays
Day 43 - Matrix Addition
Day 44 - Matrix Multiplication
Day 45 - Strings Introduction
Day 46 - String Input and Output
Day 47 - String Functions
Day 48 - String Length
Day 49 - String Copy
Day 50 - String Comparison
Day 51 - String Concatenation
Day 52 - Pointers Introduction
Day 53 - Pointer Variables
Day 54 - Pointers and Arrays
Day 55 - Pointers and Functions
Day 56 - Pointer Arithmetic
Day 57 - Multiple Pointers
Day 58 - Structures Introduction
Day 59 - Structure Variables
Day 60 - Array of Structures
Day 61 - Nested Structures
Day 62 - Unions
Day 63 - Enumerations
Day 64 - Typedef
Day 65 - File Handling Introduction
Day 66 - Reading Files
Day 67 - Writing Files
Day 68 - File Modes
Day 69 - Command Line Arguments
Day 70 - Dynamic Memory Allocation
Day 71 - malloc()
Day 72 - calloc()
Day 73 - realloc()
Day 74 - free()
Day 75 - Linked List Introduction
Day 76 - Creating a Linked List
Day 77 - Inserting in Linked List
Day 78 - Deleting from Linked List
Day 79 - Searching in Linked List
Day 80 - Stack Introduction
Day 81 - Stack Using Array
Day 82 - Queue Introduction
Day 83 - Queue Using Array
Day 84 - Circular Queue
Day 85 - Recursion Problems
Day 86 - Fibonacci Series
Day 87 - Factorial Program
Day 88 - Prime Number Problems
Day 89 - Palindrome Problems
Day 90 - Armstrong Number
Day 91 - Number Reversal
Day 92 - GCD and LCM
Day 93 - Basic C Problem Solving
Day 94 - Array Problem Solving
Day 95 - String Problem Solving
Day 96 - Pointer Problem Solving
Day 97 - Structure Problem Solving
Day 98 - File Handling Project
Day 99 - C Programming Revision
Day 100 - Final C Programming Project 
100-days-of-code-c
Day 1 - Hello World
#include <stdio.h>
int main(){ printf("Hello World"); return 0; }

Day 2 - Print Name
#include <stdio.h>
int main(){ printf("My Name is Aryash"); return 0; }

Day 3 - Variables
#include <stdio.h>
int main(){ int age=20; printf("%d",age); return 0; }

Day 4 - Data Types
#include <stdio.h>
int main(){ int a=10; float b=5.5; char c='A'; printf("%d %.1f %c",a,b,c); return 0; }

Day 5 - User Input
#include <stdio.h>
int main(){ int n; scanf("%d",&n); printf("%d",n); return 0; }

Day 6 - Addition
#include <stdio.h>
int main(){ int a,b; scanf("%d%d",&a,&b); printf("%d",a+b); return 0; }

Day 7 - Subtraction
#include <stdio.h>
int main(){ int a,b; scanf("%d%d",&a,&b); printf("%d",a-b); return 0; }

Day 8 - Multiplication
#include <stdio.h>
int main(){ int a,b; scanf("%d%d",&a,&b); printf("%d",a*b); return 0; }

Day 9 - Division
#include <stdio.h>
int main(){ int a,b; scanf("%d%d",&a,&b); printf("%d",a/b); return 0; }

Day 10 - Modulus
#include <stdio.h>
int main(){ int a,b; scanf("%d%d",&a,&b); printf("%d",a%b); return 0; }

Day 11 - Even or Odd
#include <stdio.h>
int main(){ int n; scanf("%d",&n); if(n%2==0) printf("Even"); else printf("Odd"); return 0; }

Day 12 - Positive or Negative
#include <stdio.h>
int main(){ int n; scanf("%d",&n); if(n>=0) printf("Positive"); else printf("Negative"); return 0; }

Day 13 - Largest of Two
#include <stdio.h>
int main(){ int a,b; scanf("%d%d",&a,&b); printf("%d",a>b?a:b); return 0; }

Day 14 - Largest of Three
#include <stdio.h>
int main(){ int a,b,c; scanf("%d%d%d",&a,&b,&c); if(a>b&&a>c) printf("%d",a); else if(b>c) printf("%d",b); else printf("%d",c); return 0; }

Day 15 - If Statement
#include <stdio.h>
int main(){ int n=10; if(n>5) printf("Greater"); return 0; }

Day 16 - If Else
#include <stdio.h>
int main(){ int n; scanf("%d",&n); if(n>=18) printf("Adult"); else printf("Minor"); return 0; }

Day 17 - Else If Ladder
#include <stdio.h>
int main(){ int n; scanf("%d",&n); if(n>=90) printf("A"); else if(n>=60) printf("B"); else printf("C"); return 0; }

Day 18 - Switch
#include <stdio.h>
int main(){ int n; scanf("%d",&n); switch(n){case 1:printf("Monday");break;case 2:printf("Tuesday");break;default:printf("Other");} return 0; }

Day 19 - For Loop
#include <stdio.h>
int main(){ for(int i=1;i<=10;i++) printf("%d ",i); return 0; }

Day 20 - While Loop
#include <stdio.h>
int main(){ int i=1; while(i<=10){printf("%d ",i);i++;} return 0; }

Day 21 - Do While
#include <stdio.h>
int main(){ int i=1; do{printf("%d ",i);i++;}while(i<=10); return 0; }

Day 22 - Break
#include <stdio.h>
int main(){ for(int i=1;i<=10;i++){if(i==5) break; printf("%d ",i);} return 0; }

Day 23 - Continue
#include <stdio.h>
int main(){ for(int i=1;i<=5;i++){if(i==3) continue; printf("%d ",i);} return 0; }

Day 24 - Nested Loop
#include <stdio.h>
int main(){ for(int i=1;i<=3;i++){for(int j=1;j<=3;j++) printf("* "); printf("\n");} return 0; }

Day 25 - Star Pattern
#include <stdio.h>
int main(){ for(int i=1;i<=5;i++){for(int j=1;j<=i;j++) printf("* "); printf("\n");} return 0; }

Day 26 - Number Pattern
#include <stdio.h>
int main(){ for(int i=1;i<=5;i++){for(int j=1;j<=i;j++) printf("%d ",j); printf("\n");} return 0; }

Day 27 - Reverse Pattern
#include <stdio.h>
int main(){ for(int i=5;i>=1;i--){for(int j=1;j<=i;j++) printf("* "); printf("\n");} return 0; }

Day 28 - Function
#include <stdio.h>
void hello(){printf("Hello");}
int main(){hello();return 0;}

Day 29 - Function with Parameter
#include <stdio.h>
void add(int a,int b){printf("%d",a+b);}
int main(){add(10,20);return 0;}

Day 30 - Return Function
#include <stdio.h>
int add(int a,int b){return a+b;}
int main(){printf("%d",add(10,20));return 0;}

Day 31 - Call by Value
#include <stdio.h>
void change(int x){x=100;}
int main(){int a=10;change(a);printf("%d",a);return 0;}

Day 32 - Recursion
#include <stdio.h>
void count(int n){if(n==0)return;printf("%d ",n);count(n-1);}
int main(){count(5);return 0;}

Day 33 - Array
#include <stdio.h>
int main(){int a[]={10,20,30,40,50};for(int i=0;i<5;i++)printf("%d ",a[i]);return 0;}

Day 34 - Array Sum
#include <stdio.h>
int main(){int a[]={1,2,3,4,5},sum=0;for(int i=0;i<5;i++)sum+=a[i];printf("%d",sum);return 0;}

Day 35 - Array Average
#include <stdio.h>
int main(){int a[]={10,20,30,40,50},sum=0;for(int i=0;i<5;i++)sum+=a[i];printf("%.2f",sum/5.0);return 0;}

Day 36 - Linear Search
#include <stdio.h>
int main(){int a[]={10,20,30,40},key=30;for(int i=0;i<4;i++)if(a[i]==key)printf("Found");return 0;}

Day 37 - Find Maximum
#include <stdio.h>
int main(){int a[]={10,50,20,40},max=a[0];for(int i=1;i<4;i++)if(a[i]>max)max=a[i];printf("%d",max);return 0;}

Day 38 - Find Minimum
#include <stdio.h>
int main(){int a[]={10,50,20,40},min=a[0];for(int i=1;i<4;i++)if(a[i]<min)min=a[i];printf("%d",min);return 0;}

Day 39 - Bubble Sort
#include <stdio.h>
int main(){int a[]={5,3,4,1,2};for(int i=0;i<5;i++)for(int j=0;j<4-i;j++)if(a[j]>a[j+1]){int t=a[j];a[j]=a[j+1];a[j+1]=t;}for(int i=0;i<5;i++)printf("%d ",a[i]);return 0;}

Day 40 - Selection Sort
#include <stdio.h>
int main(){int a[]={5,3,4,1,2};for(int i=0;i<5;i++){int m=i;for(int j=i+1;j<5;j++)if(a[j]<a[m])m=j;int t=a[i];a[i]=a[m];a[m]=t;}for(int i=0;i<5;i++)printf("%d ",a[i]);return 0;}

Day 41 - Insertion Sort
#include <stdio.h>
int main(){int a[]={5,3,4,1,2};for(int i=1;i<5;i++){int k=a[i],j=i-1;while(j>=0&&a[j]>k){a[j+1]=a[j];j--;}a[j+1]=k;}for(int i=0;i<5;i++)printf("%d ",a[i]);return 0;}

Day 42 - 2D Array
#include <stdio.h>
int main(){int a[2][2]={{1,2},{3,4}};for(int i=0;i<2;i++){for(int j=0;j<2;j++)printf("%d ",a[i][j]);printf("\n");}return 0;}

Day 43 - Matrix Addition
#include <stdio.h>
int main(){int a[2][2]={{1,2},{3,4}},b[2][2]={{5,6},{7,8}};for(int i=0;i<2;i++)for(int j=0;j<2;j++)printf("%d ",a[i][j]+b[i][j]);return 0;}

Day 44 - Matrix Transpose
#include <stdio.h>
int main(){int a[2][2]={{1,2},{3,4}};for(int i=0;i<2;i++){for(int j=0;j<2;j++)printf("%d ",a[j][i]);printf("\n");}return 0;}

Day 45 - String
#include <stdio.h>
int main(){char name[]="Aryash";printf("%s",name);return 0;}

Day 46 - String Input
#include <stdio.h>
int main(){char name[50];scanf("%s",name);printf("%s",name);return 0;}

Day 47 - String Length
#include <stdio.h>
#include <string.h>
int main(){char s[]="Hello";printf("%lu",strlen(s));return 0;}

Day 48 - String Copy
#include <stdio.h>
#include <string.h>
int main(){char a[20],b[]="Hello";strcpy(a,b);printf("%s",a);return 0;}

Day 49 - String Compare
#include <stdio.h>
#include <string.h>
int main(){printf("%d",strcmp("Hello","Hello"));return 0;}

Day 50 - String Concatenation
#include <stdio.h>
#include <string.h>
int main(){char a[30]="Hello ";strcat(a,"World");printf("%s",a);return 0;}

Day 51 - Pointer
#include <stdio.h>
int main(){int a=10;int *p=&a;printf("%d",*p);return 0;}

Day 52 - Pointer Address
#include <stdio.h>
int main(){int a=10;int *p=&a;printf("%p",(void*)p);return 0;}

Day 53 - Pointer and Array
#include <stdio.h>
int main(){int a[]={10,20,30};int *p=a;printf("%d",*(p+1));return 0;}

Day 54 - Pointer Function
#include <stdio.h>
void change(int *p){*p=100;}
int main(){int a=10;change(&a);printf("%d",a);return 0;}

Day 55 - Swap Using Pointer
#include <stdio.h>
void swap(int *a,int *b){int t=*a;*a=*b;*b=t;}
int main(){int a=10,b=20;swap(&a,&b);printf("%d %d",a,b);return 0;}

Day 56 - Pointer Arithmetic
#include <stdio.h>
int main(){int a[]={10,20,30};int *p=a;printf("%d",*(p+2));return 0;}

Day 57 - Structure
#include <stdio.h>
struct Student{int age;};
int main(){struct Student s={20};printf("%d",s.age);return 0;}

Day 58 - Structure String
#include <stdio.h>
struct Student{char name[20];int age;};
int main(){struct Student s={"Aryash",20};printf("%s %d",s.name,s.age);return 0;}

Day 59 - Array of Structures
#include <stdio.h>
struct Student{int age;};
int main(){struct Student s[2]={{20},{21}};printf("%d %d",s[0].age,s[1].age);return 0;}

Day 60 - Nested Structure
#include <stdio.h>
struct Address{int pin;}; struct Student{struct Address a;};
int main(){struct Student s={{380001}};printf("%d",s.a.pin);return 0;}

Day 61 - Union
#include <stdio.h>
union Data{int x;float y;};
int main(){union Data d;d.x=10;printf("%d",d.x);return 0;}

Day 62 - Enum
#include <stdio.h>
enum Day{MON,TUE,WED};
int main(){enum Day d=MON;printf("%d",d);return 0;}

Day 63 - Typedef
#include <stdio.h>
typedef int Number;
int main(){Number n=10;printf("%d",n);return 0;}

Day 64 - File Writing
#include <stdio.h>
int main(){FILE *f=fopen("data.txt","w");fprintf(f,"Hello C");fclose(f);return 0;}

Day 65 - File Reading
#include <stdio.h>
int main(){FILE *f=fopen("data.txt","r");char c;while((c=fgetc(f))!=EOF)putchar(c);fclose(f);return 0;}

Day 66 - File Append
#include <stdio.h>
int main(){FILE *f=fopen("data.txt","a");fprintf(f,"\nNew Data");fclose(f);return 0;}

Day 67 - malloc()
#include <stdio.h>
#include <stdlib.h>
int main(){int *p=malloc(5*sizeof(int));p[0]=10;printf("%d",p[0]);free(p);return 0;}

Day 68 - calloc()
#include <stdio.h>
#include <stdlib.h>
int main(){int *p=calloc(5,sizeof(int));printf("%d",p[0]);free(p);return 0;}

Day 69 - realloc()
#include <stdio.h>
#include <stdlib.h>
int main(){int *p=malloc(2*sizeof(int));p=realloc(p,5*sizeof(int));free(p);return 0;}

Day 70 - free()
#include <stdlib.h>
int main(){int *p=malloc(sizeof(int));*p=10;free(p);return 0;}

Day 71 - Command Line Argument
#include <stdio.h>
int main(int argc,char *argv[]){printf("%d",argc);return 0;}

Day 72 - Factorial
#include <stdio.h>
int main(){int n=5,f=1;for(int i=1;i<=n;i++)f*=i;printf("%d",f);return 0;}

Day 73 - Fibonacci
#include <stdio.h>
int main(){int a=0,b=1;for(int i=0;i<10;i++){printf("%d ",a);int c=a+b;a=b;b=c;}return 0;}

Day 74 - Prime Number
#include <stdio.h>
int main(){int n=17,prime=1;for(int i=2;i<n;i++)if(n%i==0)prime=0;printf(prime?"Prime":"Not Prime");return 0;}

Day 75 - Reverse Number
#include <stdio.h>
int main(){int n=123,r=0;while(n){r=r*10+n%10;n/=10;}printf("%d",r);return 0;}

Day 76 - Palindrome Number
#include <stdio.h>
int main(){int n=121,t=n,r=0;while(n){r=r*10+n%10;n/=10;}printf(t==r?"Palindrome":"Not Palindrome");return 0;}

Day 77 - Armstrong Number
#include <stdio.h>
int main(){int n=153,t=n,s=0;while(n){int d=n%10;s+=d*d*d;n/=10;}printf(s==t?"Armstrong":"Not Armstrong");return 0;}

Day 78 - GCD
#include <stdio.h>
int main(){int a=12,b=18;while(b){int t=b;b=a%b;a=t;}printf("%d",a);return 0;}

Day 79 - LCM
#include <stdio.h>
int main(){int a=12,b=18,x=a,y=b;while(y){int t=y;y=x%y;x=t;}printf("%d",(a*b)/x);return 0;}

Day 80 - Sum of Digits
#include <stdio.h>
int main(){int n=123,s=0;while(n){s+=n%10;n/=10;}printf("%d",s);return 0;}

Day 81 - Count Digits
#include <stdio.h>
int main(){int n=12345,c=0;while(n){c++;n/=10;}printf("%d",c);return 0;}

Day 82 - Stack
#include <stdio.h>
int main(){int stack[5],top=-1;stack[++top]=10;stack[++top]=20;printf("%d",stack[top--]);return 0;}

Day 83 - Queue
#include <stdio.h>
int main(){int q[5],front=0,rear=0;q[rear++]=10;q[rear++]=20;printf("%d",q[front++]);return 0;}

Day 84 - Linked List
#include <stdio.h>
#include <stdlib.h>
struct Node{int data;struct Node *next;};
int main(){struct Node *n=malloc(sizeof(struct Node));n->data=10;n->next=NULL;printf("%d",n->data);free(n);return 0;}

Day 85 - Linked List Traversal
#include <stdio.h>
#include <stdlib.h>
struct Node{int data;struct Node *next;};
int main(){struct Node a={10,NULL},b={20,NULL};a.next=&b;printf("%d %d",a.data,a.next->data);return 0;}

Day 86 - Search Array
#include <stdio.h>
int main(){int a[]={1,2,3,4,5},key=4;for(int i=0;i<5;i++)if(a[i]==key)printf("Found at %d",i);return 0;}

Day 87 - Second Largest
#include <stdio.h>
int main(){int a[]={10,30,20,50,40},max=0,second=0;for(int i=0;i<5;i++){if(a[i]>max){second=max;max=a[i];}else if(a[i]>second)second=a[i];}printf("%d",second);return 0;}

Day 88 - Remove Duplicate
#include <stdio.h>
int main(){int a[]={1,2,2,3,3},n=5;for(int i=0;i<n;i++){int d=0;for(int j=0;j<i;j++)if(a[i]==a[j])d=1;if(!d)printf("%d ",a[i]);}return 0;}

Day 89 - Matrix Multiplication
#include <stdio.h>
int main(){int a[2][2]={{1,2},{3,4}},b[2][2]={{5,6},{7,8}},c[2][2]={0};for(int i=0;i<2;i++)for(int j=0;j<2;j++)for(int k=0;k<2;k++)c[i][j]+=a[i][k]*b[k][j];printf("%d",c[0][0]);return 0;}

Day 90 - String Reverse
#include <stdio.h>
#include <string.h>
int main(){char s[]="Hello";for(int i=strlen(s)-1;i>=0;i--)printf("%c",s[i]);return 0;}

Day 91 - Character Count
#include <stdio.h>
int main(){char s[]="hello";int c=0;for(int i=0;s[i];i++)c++;printf("%d",c);return 0;}

Day 92 - Vowel Count
#include <stdio.h>
int main(){char s[]="education";int c=0;for(int i=0;s[i];i++)if(s[i]=='a'||s[i]=='e'||s[i]=='i'||s[i]=='o'||s[i]=='u')c++;printf("%d",c);return 0;}

Day 93 - Swap Without Third Variable
#include <stdio.h>
int main(){int a=10,b=20;a=a+b;b=a-b;a=a-b;printf("%d %d",a,b);return 0;}

Day 94 - Decimal to Binary
#include <stdio.h>
int main(){int n=10,b[10],i=0;while(n){b[i++]=n%2;n/=2;}while(i--)printf("%d",b[i]);return 0;}

Day 95 - Binary to Decimal
#include <stdio.h>
int main(){int n=1010,d=0,p=1;while(n){d+=(n%10)*p;p*=2;n/=10;}printf("%d",d);return 0;}

Day 96 - Simple Calculator
#include <stdio.h>
int main(){char op;float a,b;scanf("%f %c %f",&a,&op,&b);if(op=='+')printf("%.2f",a+b);else if(op=='-')printf("%.2f",a-b);else if(op=='*')printf("%.2f",a*b);else if(op=='/')printf("%.2f",a/b);return 0;}

Day 97 - Student Grade
#include <stdio.h>
int main(){int marks=85;if(marks>=90)printf("A+");else if(marks>=80)printf("A");else if(marks>=70)printf("B");else printf("C");return 0;}

Day 98 - Mini Project
#include <stdio.h>
int main(){int a,b;printf("Enter two numbers: ");scanf("%d%d",&a,&b);printf("Sum = %d",a+b);return 0;}

Day 99 - C Revision
#include <stdio.h>
int main(){int n=5;int sum=0;for(int i=1;i<=n;i++)sum+=i;printf("Sum = %d",sum);return 0;}

Day 100 - Final C Project
#include <stdio.h>
int main(){int a,b;printf("Enter two numbers: ");scanf("%d%d",&a,&b);printf("Addition = %d\n",a+b);printf("Subtraction = %d\n",a-b);printf("Multiplication = %d\n",a*b);printf("Division = %d\n",a/b);return 0;}
