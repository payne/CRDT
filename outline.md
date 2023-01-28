CRDT - 60-minute introduction

# 15 minutes: Front End Demo Time

## Demo of online collaborative text editor
Show at least one off-the-shelf opensource demo
Show at least one hand-built opensource demo

## WebRTC vs. WebSockets
Talk about pros & cons of each
### Stetch goals
1. Long polling (COMET)

## Offline first
Show at least one off-the-shelf (or better yet, hand-built) opensource demo
Cite other implementations:
Automerge.org etc
Show off automerge emailing -- network agnowstic stuff
  Or use unidirectional messaging: send an Automerge file as an email attachment or store it on a file server.

# 15 minutes: A peek behind the curtain - how it works
Remember that real computer science research is quite deep, and this is just an introduction.
Use Rudi Chen’s explanations & others -- cite sources!

## Commutative idempotent operations make synchronization easier.
Walk through the bag examples that Rudi Chen used.
Site Martin Kleperman’s videos & papers for the nuanced algorithms that are being tested

## CRDTs Yjs data structures
Map, array, json like things. Do a nod toward the design for and adopting section of the talk

# 15 minutes: CRDTs & Server side problems
CRDTs are not just an in-browser front-end utility. They can be handy on the server
CURE to the CAP problem - AntidoteDB.eu - the ideas and a demo.

## CAP theorem - AntidoteDB.eu and the CURE
Talk about the ideas and give some concrete examples.

## Java Demo and maybe a JavaScript demo too
Docker compose is my friend

# 15 minutes: Designing documents for CRDTs
How to design the data managed by your application to work well with CRDTs?

