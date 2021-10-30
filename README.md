# ML project by Tensorflow 2.0

![76627303-734f1c00-6543-11ea-9000-ff361a84e9e4 (1)](https://user-images.githubusercontent.com/81525051/139526387-516e104e-b9e5-4df2-9c14-1c65ee4b59b3.png)

There are multiple changes in TensorFlow 2.0 to make TensorFlow users more productive. TensorFlow 2.0 removes redundant APIs, makes APIs more consistent (Unified RNNs, Unified Optimizers), and better integrates with the Python runtime with Eager execution.


![76627310-764a0c80-6543-11ea-93fa-94fe5dda572d](https://user-images.githubusercontent.com/81525051/139526432-7e2166d1-ce97-4839-bf20-c282cf5333fc.gif)
)

The above shows the prediction of the network by choosing the neuron with the highest output. While the output layer values add 1 to one, these do not reflect well-calibrated measures of "uncertainty". Often, the network is overly confident about the top choice that does not reflect a learned measure of probability. If everything ran correctly you should get an animation like this:

![76627284-69c5b400-6543-11ea-94d6-170680cc71fd](https://user-images.githubusercontent.com/81525051/139526439-ce7104de-9e20-4164-84b5-0831c6d31b73.gif)
