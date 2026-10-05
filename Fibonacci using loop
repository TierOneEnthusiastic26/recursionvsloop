#include <iostream>
using namespace std;

int fib(int n);

int main()
{
    int n,fibonacci=1;
    cout<<"Enter a number: ";
    cin>>n;
    fibonacci=fib(n);
    cout<<"Fibonacci value of "<<n<<" is "<<fibonacci;

    return 0;
}

int fib(int n)
{
    if (n==1)
    return 0;
    
    else if (n==2)
    return 1;

    else
    {
        int F1=0,F2=1,F;

        for (int i=3;i<=n;i++)
        {
            F=F1+F2;
            F1=F2;
            F2=F;

        }

        return F2;
    }

}
