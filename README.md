# Deep Learning Issue Solving

Deep learning issue solving is a simple readme to track issue and solve for deep code.

**Feel free to send pull request**

## Installation Problem and Solving
* Pytorch 1.1.0 install for cuda9

```$conda install pytorch torchvision cudatoolkit=9.0 -c pytorch```

* Rouge Install Problem

Follow this [link](https://sagorbrur.github.io/install_rouge.html) to installation guide. 

## Tensorflow & Keras Issue Solving



## Pytorch Issue Solving

* **Pytorch Load Saved Model in CPU**

```py
import torch

_device = torch.device("cpu")
checkpoint = torch.load('saved_model.pt', map_location={'cuda:0': 'cpu'})

```

# **Miscellaneous**

## python2 vs python3
* Issue: Error: " 'dict' object has no attribute 'iteritems' " 

`In python3 , use dict.items() instead of dict.iteritems()`

