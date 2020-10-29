# YOWOv2

## Proposal 
https://www.overleaf.com/read/jdbqkgbfstws

## 2D&3D Weights
```
The pretrained weights can be downloaded at ./weights folder.

bash ./weights/download_pretrain_weights.bash
```

## Dataset 
### JHMDB-21

```
The JHMDB-21 dataset can be downloaded at ./datasets folder.

bash ./datasets/download_data.bash
```

### Agot-24 dataset (imbalanced)

[agot-24.zip](https://drive.google.com/file/d/1mqzVMR5ud1ZzS5h2kvAOhS_UT6D3PKJ3/view?usp=sharing)
[groundtruths_agot.zip](https://drive.google.com/file/d/1FsXRXXOfocwMPc0zj6oS0yaF58f6eeW4/view?usp=sharing)

```
The Agot-24 dataset can be downloaded at ./datasets folder.

bash ./datasets/download_agot.bash
```

## Running Experiment
### JHMDB-21
```
Running Experiment on JHMDB-21.

sh run_jhmdb-21.sh
``` 

```
Test frame_mAP on JHMDB-21.

bash run_frame_mAP_jhmdb.sh
``` 

### Agot-24 dataset (imbalanced)
```
Running Experiment on Restaurants dataset.

sh run_agot-24.sh
```

```
Test frame_mAP on Restaurants dataset.

TO DO
``` 

## Reference paper

YOWO: https://github.com/wei-tim/YOWO
