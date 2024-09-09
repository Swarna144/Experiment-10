# Experiment-10
Aim:
To study and implement Pointer Operations (call by value and call by reference)

Theory:
There are two ways to call a variable to a function for various operations.

Call by value- In the call-by-value method, function arguments are passed by copying the value of the actual parameter, ensuring the original values remain unchanged.

Call by reference- In the call-by-reference method, the memory address (reference) of the actual parameter is passed to the function, allowing direct access and modification of the original values.

CODE-
10a
```
#include<iostream>
using namespace std;

int main(){
    int a = 10;
    int*aptr=&a;

    cout<<*aptr<<endl;
    *aptr=20;
     cout<<a<<endl;

     int arr[]={10,20,30};
     cout<<*arr<<endl;

     return 0;
    }
```

10b
```
#include<iostream>
using namespace std;

int main(){
    int arr[]={10,20,30};
    cout<<*arr<<endl;

    int*ptr=arr;
    for(int i=0;i<3;i++){
        cout<<*ptr<<endl;
        ptr++;
    }

    return 0;
    }
```

OUTPUT:-

10a

![Ex-10a JPG](https://github.com/user-attachments/assets/50e66663-ebe2-4fde-af62-2ca9dd3249f8)

10b

![Ex-10b JPG](https://github.com/user-attachments/assets/731e6085-d178-4a65-bb9d-c0cf05792e69)

CONCLUSION- we learned how to use Swap value in C++


