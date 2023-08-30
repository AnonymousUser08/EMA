For reviewers who want run the code, we upload parts of the codes in the Google Colab environment:

Pytorch version: https://colab.research.google.com/drive/1FPEoI_qWJPmg0JtWhcfEUYBuAJp9Ed6L?usp=sharing

MXNet version: https://colab.research.google.com/drive/1_rBaWi-v68RBFNtVlHm4G871LCv-wIaR?usp=sharing
## Important configuration settings
```bash
learning rate: lr = 0.01
epochs = 25
batch_size = 128
workers = 50
nbyz = 0 # numbers of malicious clients 
byz_type = 'gaussian-attack' # or "bitflip_attack"
aggregation = "emvr" #"krum" or "median"
data_flag = 'tissuemnist' #bloodmnist
```
## Installation
To run this project, you'll need to install the following packages:

```bash
pip install mxnet-cu112
pip install -U mxnet
pip install gluoncv
apt-get -o Dpkg::Options::="--force-confmiss" install --reinstall netbase
pip install eventlet==0.30.0
pip install gevent
pip install pandas
pip install medmnist
```
