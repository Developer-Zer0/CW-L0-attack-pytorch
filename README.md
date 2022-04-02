# PyTorch implementation of Carlini and Wagner L0-norm based adversarial attack

Towards Evaluating the Robustness of Neural Networks Paper for the CW-L0 attack by *Carlini et.al.* : https://arxiv.org/pdf/1608.04644.pdf

GitHub link for the original TensorFlow code: https://github.com/carlini/nn_robust_attacks

## Sample test on MNIST:

![image](https://user-images.githubusercontent.com/54070758/161375798-889913f8-7773-4ee9-b06c-bb44ca96f7a2.png)

(Top row plots the original MNIST images. Middle row are the adversarial variations obtained from the code with the predicted class number on top. Classes are predicted using the trained LeCun Conv model with accuracy of 99%. Bottom row plots a histogram with prediction probabilities of all class numbers.)
