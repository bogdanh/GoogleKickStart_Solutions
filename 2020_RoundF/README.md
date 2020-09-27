PaintersDuel.cpp: The problem can be solved by dfs based on the player's turn and state of graph. One thing that need to take care of is that in some cases, we need a left shift of more than 31 bits. Say we are trying to left shift 35 bits, we need to use 1LL<<35 instead of 1<<35 (which defaults to int type and cause undefined behavior). Besides that, we take the max possible difference when it is player A's turn, and minimum possible difference when it is player B's turn. helper.py is a python script that generates test cases for this problem. One of the input-out example pair is large-in-3.txt and large-out-3.txt.

ATMQueue.cpp: python submission might TLE with N log N algorithm, but C++ is safe.

MetalBurst.py: straightforward greedy.