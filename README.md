本仓库是PydeepfakeDet的复现，修改了训练部分的数据集读取部分的代码，适应Windows上的少线程有限显存的训练，6G显存可训练，时间double or tripple。数据集也已处理好，若有需要可提issue。

## Installation

- We use Python == 3.9.0, torch==1.11.0, torchvision==1.12.0.
- Install the required packages by:
  
  `pip install -r requirements.txt`


## Data Preparation

Please follow the instructions in [DATASET.md](./DATASET.md) to prepare the data.


## Quick Start

```
python run.py --cfg resnet50.yaml
```


## Visualization tools

Please refer to [VISUALIZE.md](./VISUALIZE.md) for detailed instructions.

