# 2023-TII-SPG
This is the pytorch implementation of the [paper](https://ieeexplore.ieee.org/abstract/document/10214025/).

<img src="https://github.com/Vill-Lab/2023-TII-SPG/blob/main/imgs/SPG_framework.png" width="727">

<img src="https://github.com/Vill-Lab/2023-TII-SPG/blob/main/imgs/SPG_schematic_diagram.png" width="727">

## Training
```
python train.py --cfg configs/prw.yaml
python train.py --cfg configs/cuhk_sysu.yaml
```

## Evaluation
```
python train.py --eval --ckpt [YOUR_CKPT_PATH]
```
