# Number-recognition-system
Used Neural networks to recognize numerical digits from their handwritten counterparts.
The given program trains a neural network to recognize handwritten digits. The program first imports the necessary libraries, including TensorFlow, matplotlib, and numpy. It then loads the MNIST dataset, which is a collection of 70,000 handwritten digits. The data is split into a training set of 60,000 images and a test set of 10,000 images.

The next step is to create a neural network. The network consists of two hidden layers, each with 200 neurons. The activation function for the hidden layers is the rectified linear unit (ReLU), and the activation function for the output layer is the softmax function.

The network is then trained using the Adam optimizer. The optimizer minimizes the loss function, which is the cross-entropy loss. The training process is repeated for 3 epochs.

After the training is complete, the network is evaluated on the test set. The accuracy of the network is 98.02%.

To summarize, the code you provided trains a neural network to recognize handwritten digits. The network achieves an accuracy of 98.02% on the test set.

Here are some additional details about the code:

The function model.fit() is used to train the neural network.
The function model.evaluate() is used to evaluate the neural network on the test set.
The function plt.imshow() is used to display an image.
