# grading_system.cpp
#include <iostream>

using namespace std;

int main()
{

    double scores;

   int total_students=750;
   int results_checked=0;
   while(results_checked<total_students){
         cout<<"***GRADING SYSTEM****"<<endl;
   cout<<"please enter your exam score: ";
   cin>>scores;
   if(scores>=70){
    cout<<"exellent you had grade A"<<endl;
   }
   else if(scores>=60){
    cout<<" very good you had grade B"<<endl;
   }
   else if(scores>=50){
    cout<<"good you had grade C(you can do better)"<<endl;
   }
   else if(scores>=40){
    cout<<"you had grade D"<<endl;
   }
   else {
    cout<<"you had grade F(you are to see the exam officer for resit.)"<<endl;
   }
   }
   system("pause>0");

}
