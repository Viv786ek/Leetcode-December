class Queue {
public:
    stack<int> s;
    
    // Push element x to the back of queue.
    void push(int x) {
        pushHelper(x);
    }
    void pushHelper(int x){
        if(s.size()==0){
            s.push(x);
            return;
        }
        int data;
        data = s.top();
        s.pop();
        pushHelper(x);
        s.push(data);
        return;
        
    }

    // Removes the element from in front of queue.
    void pop(void) {
        s.pop();
    }

    // Get the front element.
    int peek(void) {
        return s.top();
    }

    // Return whether the queue is empty.
    bool empty(void) {
        return (s.size()==0);
    }
};
