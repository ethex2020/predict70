## validation_accuracy 99%       		   val_acc 99%  
## train/validation folder == acc/val_acc

Epoch 175/300

200/200 [=======================] - 45s 227ms/step - loss: 0.0134 - acc: 0.9960 - val_loss: 0.0011 - val_acc: 0.9925


## predict() on validation_accuracy-FOLDER  only accuracy 70%

#


## error solved?, now is the predict() accuracy 97.75%
No method preprocess_input() and normalization, it works! 
#

Name convention confusion ???

https://keras.io/examples/mnist_net2net/

(x_train, y_train), (x_test, y_test) = mnist.load_data()

but

acc: 0.9960 - val_loss: 0.0011 - val_acc: 0.9925

it should be renamed to

acc: 0.9960 - test_loss: 0.0011 - test_acc: 0.9925

or

(x_train, y_train), (x_val, y_val) = mnist.load_data()


#

tensorflow 2.1

keras 2.3.1

cudatoolkit 10.1.243

cudnn 7.6.5 



#
#


Kaggle Cats and Dogs Dataset

https://www.microsoft.com/en-us/download/details.aspx?id=54765

## discussion

https://github.com/keras-team/keras/issues/14099
