# Neural Networks in a Nutshell

## Installation Notes
This tutorial requires *tensorflow*, *keras* and *IPython* with the IPython Notebook. These can be installed with *pip* by typing the following in Terminal:

    pip install --upgrade pip
    pip install scipy
    pip install numpy pandas sklearn ipython matplotlib
    pip install tensorflow keras
    pip install jupyter

Next, clone the material in this tutorial using git as follows:

    git clone https://github.com/savarin/neural-networks.git

We will be reviewing the materials with the IPython Notebook. You should be able
to type

    jupyter notebook

in your terminal window and see the notebook panel load in your web browser.


## Presentation Format

This tutorial is designed to get the audience training neural networks at the end of a 1-hour session. In particular, it covers areas where neural networks really shines - CNNs and RNNs. These techniques are applied on the Kaggle Titanic, MNIST and Rotten Tomatoes datasets.

- [1-0_Prelude](https://github.com/savarin/neural-networks/blob/master/1-0_Prelude.ipynb)
- [1-1_Basic_NN-Titanic](https://github.com/savarin/neural-networks/blob/master/1-1_Basic_NN-Titanic.ipynb)
- [2-1_Basic_NN-MNIST](https://github.com/savarin/neural-networks/blob/master/2-1_Basic_NN-MNIST.ipynb)
- [2-2_Regularized_NN](https://github.com/savarin/neural-networks/blob/master/2-2_Regularized_NN.ipynb)
- [2-3_CNN](https://github.com/savarin/neural-networks/blob/master/2-3_CNN.ipynb)
- [3-3_RNN](https://github.com/savarin/neural-networks/blob/master/3-3_RNN.ipynb)
- [Appendix-SGD](https://github.com/savarin/neural-networks/blob/master/Appendix-SGD.ipynb)

Code-only versions of these notebooks can be found [here](https://github.com/savarin/neural-networks/tree/master/code).

## Credits

Special thanks for the excellent materials by Andrej Karpathy and the CS231n teaching staff, Chris Olah and Denny Britz (do check out their posts!), as well as the teams at Google TensorFlow, Keras and Kaggle.