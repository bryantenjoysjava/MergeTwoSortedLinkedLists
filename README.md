# Thoughts
I didnt have much difficulty on this problem, the only issue I was having was with a nullpointerexception on the dummy node I created, but after that was resolved, everthing worked as
it should. The algorithm involves assigning a node to the new head depending on which head in list1 and list2 is smaller, then, we use another pointer node, called last_node,
to compare the value of the nodes being tracked in each list and change the pointer of this last_node to the smaller of the two nodes being compared in the lists. If either list 
becomes null, we just simply attach the 'next' pointer of last_node to the list that still has nodes present.
