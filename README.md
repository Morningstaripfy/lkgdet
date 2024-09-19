# lkgdet

![image](https://github.com/user-attachments/assets/0ac41f51-5580-4da8-b29f-e038fea0434f)

# Dataset
* FAIR1M：[paper](https://arxiv.org/pdf/2103.05569), [download](https://gaofen-challenge.com/benchmark)
* MAR20： [paper & download](https://gcheng-nwpu.github.io/)

split dataset: [doc](https://github.com/open-mmlab/mmrotate/blob/1.x/tools/data/dota/README.md)

# Installation
create python environment
```conda
conda create --name your_env_name python=3.8.18
conda activate your_env_name
```
install pytorch, [doc](https://pytorch.org/get-started/locally/)
```conda
pip install torch==2.1.0 torchvision==0.16.0 torchaudio==2.1.0 --index-url https://download.pytorch.org/whl/cu121
```
install mm and the project [doc](https://mmrotate.readthedocs.io/en/1.x/get_started.html)
```conda
pip install -U openmim
mim install mmengine
mim install "mmcv==2.1.0"
mim install 'mmdet==3.2.0'

git clone https://github.com/Morningstaripfy/lkgdet.git
cd lkgdet
pip install -v -e .
```

We are currently organizing the code and will upload it as soon as possible.

