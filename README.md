# Multi-modal Graph Convolutional Network with Composing Contrastive Augmentations for Disease Prediction

## Prerequisites
- `Python 3.9.0`
- `Pytorch 1.12.1`
- `torch-geometric 2.2.0`
- `scikit-learn 0.24.2`
- `NumPy 1.23.5`

This code has been tested using `Pytorch` on a NVIDIA GeForce RTX 3090.

## Dataset
we provide three datasets ABIDE、ADNI、ODIR[[BaiduPan](https://pan.baidu.com/s/1Yye3bPdQyGGLPO_7BLm4vg)](code: s9rd)

## Training
```
./scripts/train_ABIDE.sh
./scripts/train_ADNI.sh
./scripts/train_ODIR.sh
```
or run
```
python train_eval.py --dataset ABIDE --type PageRank --num_classes 2 --train 1
python train_eval.py --dataset ADNI --type PageRank --num_classes 2 --train 1
python train_eval.py --dataset ODIR --type PageRank --num_classes 8 --train 1
```
