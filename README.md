# PyTorch SimCLR: A Simple Framework for Contrastive Learning of Visual Representations

This repo is based on [PyTorch SimCLR](https://github.com/c-liangyu/simclr_medmnist), added with MedMNIST datasets.

#### Examples
```bash

# PathMNIST
python run.py -data ./datasets -dataset-name PathMNIST --log-every-n-steps 100 -b 2048 --gpu-index 2 -j 32

# OrganAMNIST
python run.py -data ./datasets -dataset-name organamnist --log-every-n-steps 100 -b 2048 --gpu-index 2 -j 32

```