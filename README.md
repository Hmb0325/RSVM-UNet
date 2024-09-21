# RSVM-UNet
## 0.Main Environments
```
pip install torch==1.13.0 torchvision==0.14.0 torchaudio==0.13.0 --extra-index-url https://download.pytorch.org/whl/cu117
pip install packaging
pip install timm==0.4.12
pip install pytest chardet yacs termcolor
pip install submitit tensorboardX
pip install triton==2.0.0
pip install causal_conv1d==1.0.0
pip install mamba_ssm==1.0.1 
pip install scikit-learn matplotlib thop h5py SimpleITK scikit-image medpy yacs
```
## 1.Prepare the datasets
### 1.1 Synapse datasets
 - Please follow [Swin-UNet](https://github.com/HuCaoFighting/Swin-Unet) to download the dataset.
 - Put them into './data/Synapse'
 - Change the 'data_path' attribute in the 'configs/config_setting_synapse' file to yourselfs.
### 1.2 Polyp-related datasets
 - Please download the dataset from [PraNet] (https://github.com/DengPingFan/PraNet).
 - Put them into './data/Polyp'
 - Change the 'data_path' attribute in the 'configs/config_setting' file to yourselfs.
## 2. Prepare the pre_trained weights
The weights of the pre-trained VMamba could be downloaded [here](https://github.com/MzeroMiko/VMamba).
