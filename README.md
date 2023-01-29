# SCRN----Pre-Alpha-version

# Attention: before using this in any way please watch the license. Private agreement with the author is needed before using this software or any kind of it's copies.




This paper is a proposal for a new type of neural network, Self-Control Reservoir Network. All what is written in this paper has not been proved yet and would need more studies to be confirmed.

Self-Control Reservoir Network is a neural network concept that inspires from the human brain and from Reservoir Computing, designed for a better and smarter computing network.
The way it differs from Reservoir Computing and Echo State Networks is that:
- all internal weights of the reservoir are trained and not left random
- control nodes can “control” the information flow through the network and perform decisions on the reasoning process, like if accepting or not the input or like looping many times the state update until an output is accepted.
This ‘control’ feature makes neural networks much more like the human brain since this network isn’t forced to return immediately an output like in standard RNN but can loop internally for a variable number of times until an output is accepted by the control system. This is like reasoning in the human brain: looping many times neuronal circuits processes until we obtain something acceptable.
The controls also act on the input: the network can decide to ignore an input for better attention on the reasoning process (like our brain does).
This control nodes and parameters are also trainable, so this network can learn the best policy to accept or not inputs or to loop the network so that it maximizes its performances.
This network, if built properly, is Turing Complete and can perform any calculation, since it inherits the properties of recurrent neural networks, but this Turing-Completeness is enhanced if compared to traditional Recurrent Neural Networks, because the looping process allows us to perform more complex and iterative procedures on the inputs and the states with a smaller number of nodes. 
Since this architecture is strongly connected, recurrent, and since control nodes create non-continuous effects, training is more difficult and can’t rely only on gradient-descent like algorithms but must be based on some non-differential and non-continuous (zeroth-order) algorithms like genetic algorithm, Hebbian learning, simulated annealing, or Reinforcement Learning.


complete paper at the link:
