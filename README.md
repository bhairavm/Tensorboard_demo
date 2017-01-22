# Tensorboard_demo
In this repo, there are 2 versions of the classifier, a simple one and a complex one. Input_data.py retrieves and formats the [MNIST character dataset](http://yann.lecun.com/exdb/mnist/).


#Requirements
*[Tensorflow](https://www.tensorflow.org/versions/r0.10/get_started/os_setup.html)

#Usage

Once you have Tensorflow installed, just run 

```
python simple.py
```
or 
```
python complex.py
```

to train your model. You can view the results in Tensorboard after training by typing the following into terminal

```
tensorboard --logdir=./logs/nn_logs
```
Terminal will output an address to visit in your browser. Go to that address to see your tensorboard. That's it!

# Credits

The Tensorflow team at Google! I've merely created a wrapper around this code to make it easy to use.

