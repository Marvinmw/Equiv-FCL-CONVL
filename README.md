# Equiv-FCL-CONVL

An equivalence of fully connected layer and convolutional layer.

## Dependence packages

```
  * numpy
  * python3
  * tensorflow
  * keras
  * panda
  * h5py
  * matplotlib
  * skimage
```
  
## Python files

```
  * trainnetworks.py        # train CNN and FC network
  * visiualNet.py           # plot the architecture of the networks
  * computeFnorm.py         # compute F-norm of the outputs of the CONV layer and the dense layers, plot historams of the wights and filters
  * net.py                  # define CNN network
  * img2col.py              # converting 4D data to 2D matrix
  * Data.py                 # data provider
  * plotcsv.plotHistory     # plot the training and validation loss
  * logger.BachLosses.py    # record the loss of every batch
```
### Runing programs
```
    * train the two network `python3 trainnetworks.py`. The log file and model are stored in the directory logs and model.
    * visiualize the two network `python3 visualNet.py`. The reulsts are stored in the logs directory.
    * compare the two well-tuned network, `python3 computeFnorm.py`.
```
## Authors

- [Wei Ma](https://github.com/Marvinmw)
- [Jun Lu](https://github.com/junlulocky)

## References

  1. Program [hipsternet](https://github.com/wiseodd/hipsternety)
  2. Andrea Vedaldi and Karel Lenc. Matconvnet: Convolutional neural networks for matlab. In Proceedings
     of the 23rd ACM international conference on Multimedia, pp. 689–692. ACM, 2015.

