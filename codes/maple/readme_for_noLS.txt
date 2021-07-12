There are time related paprameter for switching branching method from LRB to VSIDS 
by 2500s in Maple, this can lead to unstable results on computers. Therefore, we changed 
the switch strategy by restart times. Considering that the speed of some large instances
is quite slow, in order to make sure that most examples switch at least once, we set the 
parameter for swtich to 500. This method can only improve stability, but cannot improve 
the performance. In this process, it is possible that the restart policy will also be 
modified.