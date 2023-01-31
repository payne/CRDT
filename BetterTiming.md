CRDT in 60 minutes

Google docs allows concurrent editting by many people.

Conflict free replicated data types let you write applications that:
1. Allow concurrent editting by many people
1. Allow the application to work offline
1. Allow distant data centers better coordination

# Demos to show
1. Shared text editting with presence
1. Shared JSON document editting (reflecting in web page) - Maybe Mermaid.js
1. https://www.antidotedb.eu demo
1. https://automerge.org/ email attachement demo

## Tool name dropping
1. github codespaces
1. gitpod.io
1. REPL.it

# Talk Timeline
## 5 minute introduction (end at 5 minutes)
1. locks, synchronization, mutexes, semaphores are ways to deal with conflicts when updating data around **critical sections** of code.
    1. That might not apply because these ^^^ are for multithreaded or multiprocess 
    1. Better to point out we're dealing with the databse server on a seperate computer from the application
1. In 2011 computer scientists started developing conflict free replicated data types (CRDT).
1. Imaging a like or rating feature on a website.
    1. Old way: 
        1. Start critical section
        1. read the value, 
        1. compute new value 
        1. write the value
        1. End critical section

## Criticism of CRDTs
1. https://blog.kevinjahns.de/are-crdts-suitable-for-shared-editing/


## Java Demo of AntidoteDB
https://github.com/AntidoteDB/antidote-java-tutorial

