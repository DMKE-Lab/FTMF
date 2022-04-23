# FTMF
FTMF: Few-shot temporal knowledge graph completion based on meta-optimization and Fault-tolerant mechanism
This repository contains the implementation of the FTMF architectures described in the paper.
# Installation
 Install Pytorch (>= 1.1.0)
 ```
pip install pytorch
```
 Python 3.x (tested on Python 3.6)
  ```
pip install python 3.6
```
 Numpy
  ```
pip install numpy
```
 Pandas
  ```
pip install pandas
```
 tqdm
  ```
pip install tqdm
```
# How to use
run the code:
```
python train.py 
```

# Dateprocess
To run our code, we need to divide the data set according to the data set partition file first, or divide it according to our own needs. If we want to get the best results, we need to use Complex to pre-train and then embed it into the model.
# Baselines
TransE  
DistMult  
TTransE  
TA-TransE  
TA-DistMult  
RE-Net  
GMatching  
MateR  
FSRL
