# Assignment_BTech2026_-2201920130161.
IT-C (04/02/2025)

#include <bits/stdc++.h> 
#include<iostream>

using namespace std;

class Person {

    private:
      string name;
    int age;

    public:
    void setValue(string name,int age){
        this->name=name;
        this->age=age;
    }

    void getValue(){
        cout<<"The name of the person is "<<name<<" and the age is "<<age<<"."<<endl;;
        
    }

};

int main() {

    Person p;
    string n;
    cin>>n;
    int a;
    cin>>a;
    p.setValue(n,a);
    p.getValue();

    return 0;
}
