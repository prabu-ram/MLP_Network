# MLP_Network

Here is a Multilayer Perceptron Neural Network from scratch just using Numpy.
configuration: <br>

*"layers": [ <br>
{ <br>
"size": 784,  {MNIST Data Set} <br>
"name": "input_layer", <br>
"type": "input" <br>
}, <br>
{ <br>
"size": 128, <br>
"name": "hidden_layer", <br>
"type": "RelU or TanH" <br>
}, <br>
{ <br>
"size": 10, <br>
"name": "output_layer", <br>
"type": "softmax" <br>
} <br>
]* <br>
<br> <br>
Usage of this MLP is given in MLP Playground file where it is trained on MNIST Dataset and have used RelU and TanH as activations
<br><br>
**USAGE:**
Download MLP.py and import "MLPNetwork" to your file, Initialize the parameters and use it.
