python-chord
============

Python **Chord** implementation, [paper available here](http://pdos.csail.mit.edu/papers/chord:sigcomm01/chord_sigcomm.pdf).

Currently supports concurrent addition of peers into the network and node failures/leave. Will implement better tests soon.

Some key lookup consistency test implemented in test.py, and nodes distribute keys accordingly to node joins.

### How to test?
- `$>python test.py` to check consistency.
- `$>python create_chord.py $N_CHORD_NODES` to run a DHT that lets you ask questions to random members.

### What's next?

- Implement some source of replication
- Build a decentralized and replicated user-space file system

**DISCLAIMER**
Pet project for fun to learn about DHT's, not intended to be used in real life.

Other projects:
 - Comming soon