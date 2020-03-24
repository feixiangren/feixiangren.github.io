Machine Learning Algorithms - A Brief Overview. Series on Vol.2 of my planning book, this is Artificial Intelligence Algorithms part.

## 1. Machine Learning Algorithms

### Deep Learning: Convolutional Neural Networks (CNN)

#### Convolution Layers

$${x_{j}^{l}} = f \left( \sum_{i \in M_{j}} {x_{i}^{l-1}} * k_{ij}^{l} + b_{j}^{l} \right ) \quad(1)$$

##### Computing the gradients
$${\delta _{j}^{l}} = \beta _{j}^{l+1}\left ( f'( u_{j}^{l}) \circ  up(\delta_{j}^{l+1}) \right)$$

$$\frac{\partial E}{\partial k_{ij}^{l}}= \sum_{u,v}(\delta_{l}^{j})_{uv} (p_{i}^{l-1})_{uv}$$

#### Sub-sampling Layers
$$x_{j}^{l} = f\left (\beta_{j}^{l}down(x_{j}^{l-1}) + b_{j}^{l} \right) \quad(2)$$

#### Learning Combinations of Feature Maps
$$x_{j}^{l} = f\left ( \sum_{i=1}^{N_{in}}a_{ij}(x_{i}^{l-1} * k_{i}^{l}) + b_{j}^{l} \right) \quad(3)$$

subject to the constraints %%\sum_{i}a_{ij} = 1 \; and \; 0\leq a_{ij} \leq 1%%.

## 2. Mathematics for Machine Learning
* Multivariable Calculus
* Linear Algebra
* Probability Theory

## 3. Programming for Machine Learning
### Python
* numpy, scipy, pandas
* scikit-learn for machine learning
* PyTorch for deep learning

### Golang
* golearn

## References
* [Stanford Coursera - Machine Learning](https://www.coursera.org/learn/machine-learning)
* [deeplearning.ai - Deep Learning Algorithms](https://www.deeplearning.ai)
