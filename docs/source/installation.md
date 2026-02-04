# Installation

## System Requirements

### Software requirements

#### OS Requirements

This package is supported for *Linux*. The package has been tested on the following systems:

- Linux: Ubuntu 22.04

## Installation Guide

You can create an environment to run SpaLP without any problems by following the code below:

```bash
git clone https://github.com/dbjzs/SpaLP.git
cd SpaLP
conda create -n SpaLP -c conda-forge python==3.10.13 libopenblas=0.3.25 -y
conda activate SpaLP
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install .
