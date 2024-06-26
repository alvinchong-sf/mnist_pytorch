## Installation
### Anaconda commands to run PyTorch
> First install Anaconda https://www.anaconda.com/download

> Install Jupynote book extension if using VScode as IDE

```bash
conda create --name <env_name>

conda env list

conda activate <env_name>

# shows all package in an anaconda environment
conda list

# check your settings in https://pytorch.org/get-started/locally/
conda install pytorch::pytorch torchvision torchaudio -c pytorch

# installs pytorch lightning. note we can usep pip inside conda activated environment
pip install lightning
pip install matplotlib

touch mnist.ipynb

# deactivate the current env
conda deactivate
```

### How to run TB Logs
```bash
# install tensorboard
pip install -U 'tensorboard'

# install tensorboardX
pip install -U 'tensorboardX'

# run tensorboard in anaconda
tensorboard --logdir tb_logs
```

## Predict Black & White hand drawn digits(MNIST)
Build MNIST model three ways 
1.  From Scratch.
2.  Regular PyTorch.
3.  Using PyTorch Lightning.

