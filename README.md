# putty_receivers_3layer
modeling the receivers from the pyow-hack game with a 3 layer neural network

Initial code uses standard gradient descent backprop learning dynamics as proof of concept. A 3-layer network with a two node hidden layer bottleneck can acquire the desired dispositions. Combinatorially, the two node bottleneck implies that output from both nodes is neccessary information in producing the desired output; and hence entails that there is something like connection in content between AB and BA where: 
AA = strong output from node 1 and strong output from node 2
AB = strong output from node 1 and weak output from node 2
BA = weak output from node 1 and strong output from node 2
BB = weak output from node 1 and weak output from node 2
That neural networks can produce this sort of behavior is already known (e.g. Oaksford and Chater (2010) "Cognition	and	Conditionals:	Probability	and	Logic	in Human	Thinking" chapter 17). However, these networks are not biologically plausible representations of cognition. So the main project is to develop a spiking neural network with spike time dependent plasticity learning dynamics and then analyze results from those networks in hopes of finding the desired type of content connection between something like AB and BA intermediary respresentations.
