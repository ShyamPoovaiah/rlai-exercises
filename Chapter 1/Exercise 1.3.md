# Exercise 1.3: Greedy Play   

## Question
Suppose the reinforcement learning player was greedy, that is, it always played the
move that brought it to the position that it rated the best. Would it learn to play better, or worse,
than a non-greedy player? What problems might occur?

## Answer:
In general it would play worse. 
1. THe chance the correct action for a situation in the long run is the first one
that returns a positive reward is pretty slim, particularly if there are a large number of actions available.
2. It would also be unable to adapt to opponents that slowly **Altered Behaviour** over time.
3. Also setting up **'multi move traps'** requires making non-greedy moves in the current state.
