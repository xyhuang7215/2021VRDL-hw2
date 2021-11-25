## VRDL HW2

## Requirements

If you are using colab, you can skip installation.
```setup
pip install -r requirements.txt
```

## Training

```train
python train.py --data data/mine.yaml --device 0 --epoch 50
```

## Evaluation

```eval
python inference.py --source ../dataset/images/test --weights ./best.pt
```

## Pre-trained Models

You can download pretrained models here:

- [My model](https://drive.google.com/file/d/19QbhDOJpgr2J3ijU-u3zZOKIc6f-m343/view?usp=sharing)

## Dataset

SVHN dataset in yolo format:

- [Data](https://drive.google.com/file/d/1vRaEcB6mOQJw2q03NBXOuf9GO_7tY70S/view?usp=sharing)

## Results

| Model name         |mAP:0.5:0.95     |
| ------------------ |---------------- |
| w/ flipping        |    0.407923     |
| w/o flipping       |    0.41016      |

## Reference

- [PyTorch_YOLOv4](https://github.com/WongKinYiu/PyTorch_YOLOv4)
