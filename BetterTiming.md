CRDT in 60 minutes

# 5 minute introduction
1. locks, synchronization, mutexes, semaphores are ways to deal with conflicts when updating data around **critical sections** of code.
1. In 2011 computer scientists started developing conflict free replicated data types (CRDT).
1. Imaging a like or rating feature on a website.
    1. Old way: 
        1. Start critical section
        1. read the value, 
        1. compute new value 
        1. write the value
        1. End critical section

