//String-coping-strcpy-
//Coping of two string in classes, c++,Oop 
#include<iostream>
#include<cstring>
using namespace std;
class stringg{
	public:
		char st1[20],st2[20];
		void get_Data(){
			cout<<"Enter 1st string : "<<endl;
			cin>>st1;
			cout<<"Enter 2nd String : "<<endl;
			cin>>st2;
			}
				void set_Data(){
					strcpy(st1,st2);
			cout<<"Coping  string st2 with st1 : "<<st1<<endl;
			
			}
};

int main(){
	stringg tt;
	tt.get_Data();
	tt.set_Data();
	
	return 0;
}
