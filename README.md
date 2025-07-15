# Experiment-3
Aim: To study and implement Operators in C++
Theory:
Arithmetic Operators
Used for basic math:
- + → Addition (a + b)
- - → Subtraction (a - b)
- * → Multiplication (a * b)
- / → Division (a / b)
- % → Modulus (remainder) (a % b)

📝 Assignment Operators
Used to assign or update values:
- = → Assign (a = b)
- += → Add and assign (a += b)
- -= → Subtract and assign (a -= b)
- *= → Multiply and assign (a *= b)
- /= → Divide and assign (a /= b)
- %= → Modulus and assign (a %= b
Relational Operators
Used to compare values (returns true or false):
- == → Equal to (a == b)
- != → Not equal to (a != b)
- > → Greater than (a > b)
- < → Less than (a < b)
- >= → Greater than or equal to (a >= b)
- <= → Less than or equal to (a <= b)

🔀 Logical Operators
Used in conditions and decision-making:
- && → Logical AND (a && b)
- || → Logical OR (a || b)
- ! → Logical NOT (!a)

🧠 Bitwise Operators
Used to manipulate bits directly:
- & → Bitwise AND (a & b)
- | → Bitwise OR (a | b)
- ^ → Bitwise XOR (a ^ b)
- ~ → Bitwise NOT (~a)
- << → Left shift (a << 1)
- >> → Right shift (a >> 1)

🔁 Increment & Decrement Operators
Used to increase or decrease values:
- ++ → Increment (++a or a++)
- -- → Decrement (--a or a--)

🎯 Other Useful Operators
- ?: → Ternary (conditional) operator
- sizeof → Returns size of a data type
- typecast → Converts one type to another
- , → Comma operator (evaluates multiple expressions)
Code:
  EXP 3.1
#include<iostream>
using namespace std;
int main()
{
    int a;
    cout<<"Enter a number"<<endl;
    cin>>a;
    if (a==0)
    {
    cout<<"The number is zero"<<endl;
    }
    else if (a>0)
    {
    cout<<"positive"<<endl;
    }
    else
    {
        cout<<"negative"<<endl;
    }
}
Output:
Enter a number
56
positive


Part 2:
#include<iostream>
using namespace std;
int main()
{
    int m1,m2,m3,m4,m5;
    cout<<"Enter a marks of subject 1"<<endl;
    cin>>m1;
    cout<<"Enter a marks of subject 2"<<endl;
    cin>>m2;
    cout<<"Enter a marks of subject 3"<<endl;
    cin>>m3;
    cout<<"Enter a marks of subject 4"<<endl;
    cin>>m4;
    cout<<"Enter a marks of subject 5"<<endl;
    cin>>m5;
    double avg;
    avg=(m1+m2+m3+m4+m5)/5;
    cout<<"Pecentage: "<<avg<<"%"<<endl;
    if (avg>90)
    {
        cout<<"O"<<endl;
    }
     else if (avg>85)
    {
        cout<<"A"<<endl;
    }
    else if (avg>75)
    {
        cout<<"B"<<endl;
    }
     else if (avg>65)
    {
        cout<<"C"<<endl;
    }
    else
    {
        cout<<"Fail"<<endl;
    }
}
Output:
Enter a marks of subject 1
56
Enter a marks of subject 2
85
Enter a marks of subject 3
45
Enter a marks of subject 4
85
Enter a marks of subject 5
98
Pecentage: 73%
C

