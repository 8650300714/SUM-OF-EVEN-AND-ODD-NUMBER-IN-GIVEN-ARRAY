# SUM-OF-EVEN-AND-ODD-NUMBER-IN-GIVEN-ARRAY
#include<iostream>
using namespace std;
int main(){
    int num,arr[100];
    cout<<" enter the  size of array "<<endl;
    cin>>num;
    for(int i=0;i<num;i++){
        cout<<"enter the element of array "<<i+1<<":---> ";
        cin>>arr[i];}
        int sumeven=0,sumodd=0;
        for(int i=0;i<num;i++){
            if(arr[i] % 2 ==0){
                sumeven=sumeven+arr[i];
                
            }
                else
                {
                    sumodd=sumodd+arr[i];
                }
            }
            cout<<"the sum even number"<<sumeven<<endl;
            cout<<"the sum of odd number"<<sumodd;
            return 0;
    
}
