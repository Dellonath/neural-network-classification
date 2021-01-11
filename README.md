# Neural Network to Classification Multiclass  

My first implementation of a Neural Network! The purpose of this is to apply my studies about Deep Learning, specifically feed foward, matrix multiplication, partial derivatives and backpropagation algorithm.

### Description
This Neural Network takes points scattered in a three-dimentional space and classifies them in 3 possible classes:
* Class Yellow: (1, 0, 0)
* Class Green:  (0, 1, 0)
* Class Purple: (0, 0, 1)
<br> The Dataset contains 500 random samples, each one with 3 features (x, y, z coordinates) and was ploted below in a 3D Scatter Plot:

<img src = "https://user-images.githubusercontent.com/56659549/104233069-02f97b80-5430-11eb-9936-5a1737ec0f0f.png" height = "350" widht = "400">

### Libraries used
- **Numpy** for NN implementarion
- **Matplotlib** for stats visualization
- **Sklearn** for dataset generation and normalization

### Structure
|  Layer  |Activation Function|Number of Neurons  |
|---------|-------------------|-------------------|
| Input   |         -         |3                  |
| Hidden1 |      Linear       |3                  |
| Hidden2 |      Relu         |3                  |
| Output  |      Softmax      |3                  |

The **cost** was calculated with Neg-LogLikelihood function.

<img src = "https://user-images.githubusercontent.com/56659549/104227713-95961c80-5428-11eb-89b7-b438986a19c8.png" height = "350" widht = "400">




### References

- [Neural Network from Scratch](https://beckernick.github.io/neural-network-scratch/)
- [Backpropagation Algorithm](https://theclevermachine.wordpress.com/tag/backpropagation-algorithm/)
- [Back-Propagation is very simple. Who made it Complicated ?](https://becominghuman.ai/back-propagation-is-very-simple-who-made-it-complicated-97b794c97e5c)
- [A Step by Step Backpropagation Example](https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/)
- [Understanding softmax and the negative log-likelihood](https://ljvmiranda921.github.io/notebook/2017/08/13/softmax-and-the-negative-log-likelihood/)
