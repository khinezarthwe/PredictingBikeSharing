### Meets Specifications
Congratulations on completing the project :tada:
Happy Learning :relaxed:

### Code Functionality
##### All the code in the notebook runs in Python 3 without failing, and all unit tests pass.
```- All unit tests passed :thumbsup:```

##### The sigmoid activation function is implemented correctly

```
- Sigmoid was implemented correctly. Please remove unnecessary comments
```

### Forward Pass
-  The forward pass is correctly implemented for the network's training.

- The run method correctly produces the desired regression output for the neural network.

### Backward Pass
-  The network correctly implements the backward pass for each batch, correctly updating the weight change.

- Updates to both the input-to-hidden and hidden-to-output weights are implemented correctly.

### Hyperparameters
##### The number of epochs is chosen such the network is trained well enough to accurately make predictions but is not overfitting to the training data.
```bash
- The model reaches the desired loss values and it's not overfitting :clap:
```

##### The number of hidden units is chosen such that the network is able to accurately predict the number of bike riders, is able to generalize, and is not overfitting.
```bash
- Good choice of number of hidden_nodes. If you ever have trouble determining the number of hidden nodes, remember a good rule of thumb is the halfway in between the number of input and output units.
```

##### The learning rate is chosen such that the network successfully converges, but is still time efficient.
```bash
- The learning rate is chosen correctly :thumbsup:
- If you look at the update_weights method you have written, you can see this line self.weights_input_to_hidden += self.lr * delta_weights_i_h / n_records
Our multiplication factor is self.lr/n_records, we want this value to be around 0.005 - 0.01, so, choose your learning rate accordingly,

```

##### The number of output nodes is properly selected to solve the desired problem.

- The training loss is below 0.09 and the validation loss is below 0.18.

```The validation and training loss values meet specification.

Note:- The notebook doesn't display the values at 100% progress. I had to run your code locally to see the final result.
Please change your code so that it shows the final loss values before uploading it to github.```
