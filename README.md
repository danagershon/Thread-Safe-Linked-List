# Thread Safe Linked List

Operating System Course HW3: Thread Safe Linked List in C++

• Multi-threaded sorted singly linked list implementation

• Providing fine-grained locking using hand-over-hand locking

• Insertion and removal operations may be called concurrently

• Operations involving different nodes will wait for each other only if strictly necessary

• Each node in the list has a separate lock
