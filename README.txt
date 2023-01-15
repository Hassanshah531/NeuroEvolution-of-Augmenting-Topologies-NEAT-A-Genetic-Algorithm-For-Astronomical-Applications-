Traditionally a neural network topology is chosen by a human experimenter, and effective connection weight 
values are learned through a training procedure. This yields a situation whereby a trial and error process 
may be necessary in order to determine an appropriate topology. NEAT is an example of a topology and weight 
evolving artificial neural network (TWEANN) which attempts to simultaneously learn weight values and an 
appropriate topology for a neural network.

In order to encode the network into a phenotype for the GA, NEAT uses a direct encoding scheme which means 
every connection and neuron is explicitly represented. This is in contrast to indirect encoding schemes which
define rules that allow the network to be constructed without explicitly representing every connection and 
neuron allowing for more compact representation.

The NEAT approach begins with a perceptron-like feed-forward network of only input neurons and output neurons. 
As evolution progresses through discrete steps, the complexity of the network's topology may grow, either by 
inserting a new neuron into a connection path, or by creating a new connection between (formerly unconnected) 
neurons.