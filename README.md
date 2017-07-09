# tf-stanford-tutorials
This repository contains code examples for the course CS 20SI: TensorFlow for Deep Learning Research. <br>
It will be updated as the class progresses. <br>
Detailed syllabus and lecture notes can be found here http://cs20si.stanford.edu

# Note (as of July 6, 2017)
I haven't checked this repo in a while and it seems like it really needs to be updated. I'll go over all the issues this weekend.
This repository is currently in TF 0.12. I'm currently in the process of transitioning it to TF1.1. I will update the repo when this is done.


## Models include: <br>
### In the folder "examples": <br>
Linear Regression with Chicago's Fire-Theft dataset<br>
Logistic Regression with MNIST<br>
Word2vec skip-gram model with NCE loss<br>
Convnets with MNIST<br>
Autoencoder (by Nishith Khandwala)<br>
Deepdream (by Jon Shlens)<br>
Character-level language modeling <br>
<br>
### In the folder "assignments":<br>
Style Transfer<br>
Chatbot using sequence to sequence with attention<br>
<br>
## Misc<br>
Examples on how to use data readers, TFRecord<br>
Embedding visualization with TensorBoard<br>
Usage of summary ops<br>
Exercises to be familiar with other special TensorFlow ops<br>
Demonstration of the danger of lazy loading <br>
Convolutional GRU (CRGU) (by Lukasz Kaiser)


## References<br>

### Tutorials<br>
The following links are the aforementioned excellent tutorials in the [slides](http://web.stanford.edu/class/cs20si/syllabus.html):

  - ***Sebastian Ruder***: [An Overview of Gradient Descent Optimization Algorithms](http://ruder.io/optimizing-gradient-descent/)
  - ***Danijar Hafner***: [Structuring Your TensorFlow Models](http://danijar.com/structuring-your-tensorflow-models/)

### Papers<br>
The following papers will be very useful for understanding the course further more:

  - Bengio, Yoshua. ***"[Practical recommendations for gradient-based training of deep architectures.](https://arxiv.org/pdf/1206.5533.pdf)"*** Neural networks: Tricks of the trade. Springer Berlin Heidelberg, 2012. 437-478.