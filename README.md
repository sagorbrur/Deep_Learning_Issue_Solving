# Deep Learning Issue Solving

Deep learning issue solving is a simple readme to track issue and solve for deep code.

**Feel free to send pull request**

## Tensorflow & Keras Issue Solving



## Pytorch Issue Solving

* **Pytorch Load Saved Model in CPU**

```py
import torch

_device = torch.device("cpu")
checkpoint = torch.load('saved_model.pt', map_location={'cuda:0': 'cpu'})

```


