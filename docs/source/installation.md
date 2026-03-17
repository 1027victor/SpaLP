# Installation

## System Requirements

#### OS Requirements

This package is supported for *Linux*. The package has been tested on the following systems:

- Linux: Ubuntu 22.04

## Installation via github

You can create an environment to run SpaLP without any problems by following the code below:

#### 📥 Download
```
git clone https://github.com/dbjzs/SpaLP.git
cd SpaLP
```
#### 🔧 environment
SpaLP is available for Python 3.10. We recommend to train SpaLP models on a device with GPU support.  
* Using the conda install environment
```
conda create -n SpaLP -c conda-forge python==3.10.13 libopenblas=0.3.25 -y
conda activate SpaLP
```
#### 🛠️package
* Then using pip install SpaLP.
```
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install .
```

#  Installation via pypi

```
conda create -n SpaLP -c conda-forge python==3.10.13 libopenblas=0.3.25 -y
conda activate SpaLP
pip install SpaLP
```