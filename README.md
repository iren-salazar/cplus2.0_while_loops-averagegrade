# cplus2.0_while_loops-averagegrade
average grade using c++ while loops

#include <iostream>
using namespace std;
int main ()
{
    int num;
    int num1, num2, num3, num4, num5;
    int average;

    cout << "Salazar, Iren Mercado" << endl;
    
    
    cout << " Enter a number: " << endl;
    cin >> num1;
    average = num1;
    
    cout << "Enter a number: " << endl;
    cin >> num2;
    while (num2 < average)
    {
      average = num2;
    }
    cout << "Enter a number: " << endl;
    cin >> num3;
    while (num3 < average) 
    {
      average = num3;
    }
    cout << "Enter a number: " << endl;
    cin >> num4;
    while (num4 < average)
    {
      average = num4;
    }
    cout << "Enter a number: " << endl;
    cin >> num5;
    while (num5 < average) 
    {
      average= num5;
    }
    cout << average<< " Is the average grade." << endl;
    return 0;
}
  /*
                                                      
  Salazar, Iren Mercado
 Enter a number: 
90
Enter a number: 
90
Enter a number: 
87
Enter a number: 
98
Enter a number: 
90
87 Is the average grade.  */
