# STL
fuctions used in stack and queue
#include<iostream>
#include <stack>
#include <queue>
using namespace std;

void stackoperation(){
    stack<int> s;
    
    cout<<"        STACK OPERATION       "<<endl;
    s.push(10);
    s.push(20);
    s.push(30);
    
    
    cout<<"Top element is : ";
    cout<< s.top()<<endl;
    
    // cout<<"Removing a top element: ";
    //cout<<s.pop();
    
    
    cout<<"Size of stack: ";
    cout<<s.size()<<endl;
    
    cout<<"Empty: ";
    cout<<s.empty()<<endl;
    
    
    
    
    
    
    
}

void queueopertion(){
    queue<int> q;
    
    cout<<"     \n         QUEUE OPERATION\n";
    q.push(100);
    q.push(200);
    q.push(300);
    
    
    cout<<"Front element: ";
    cout<<q.front()<<endl;
    
    
    cout<<" Back element: ";
    cout<<q.back()<<endl;
    
    
    
    cout<<"size of queue: ";
    cout<<q.size()<<endl;
    
    
    
    cout<<"empty: ";
    cout<<q.empty();
    
    
}
int main(){
    stackoperation();
    queueopertion();
}

#My first chnage using local git