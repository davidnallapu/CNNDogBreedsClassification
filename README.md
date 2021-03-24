# CNNDogBreedsClassification
 This study aims to classify dog breeds. Hyperparameter tuning will be done to understand the performance of the hyperparameters. This study looks at the impact of changing the actiovation function, cost function, no. of epochs, gradient estimation, network architecture, network initialization. We will see loss, accuracy and other metrics on TensorBoard to understand performance . We will also see that certain paramerter tuning causes a dramatic difference. The findings from this study indicate that it is important to do hyper parameter tuning for Deep Learning with CNNs.

## Conclusion
We can conclude that hyperparameters are paramount in CNNs.Leaky-relu performs better than relu from our study. NLL-Loss alogirthm does better than cross-entropy from our study. Increasing from 5 to 10 has increased the accuracy. There is no plateuing at this point. Simulation needs to be run for more epochs on a faster cpu for more information. Adam optimizer seems to always do better than stochasatic gradient here. Stochastic Gradient's loss seems to be constant hence I'm not running it in my simulation.Increasing the no. of hidden layers from 3 to 4 increases the accuracy to a large extent for this problem. Xavier weights initialization leads to an increase in accuracy compared to the default torch init in most simulations. We achieve an accuracy of 96.7% accuracy over 21 epochs with Leaky-Relu, Adam Optimizitation, and NLL Loss with 4 hidden layers.

## References
[1]: Dataset : https://www.kaggle.com/miljan/stanford-dogs-dataset-traintest#

[2]: CNN : https://www.datacamp.com/community/tutorials/cnn-tensorflow-python 

[3]: PyTorch : https://medium.com/@thinkai.org/using-pytorch-for-building-a-convolutional-neural-network-cnn-model-6e47ffb61b88

[4]: Classification : https://www.analyticsvidhya.com/blog/2019/10/building-image-classification-models-cnn-pytorch/

[5]: Classification :https://becominghuman.ai/building-a-convolutional-neural-network-cnn-model-for-image-classification-116f77a7a236

## Licensing

Copyright 2021 David Samuel Nallapu
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
