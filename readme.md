# Probabilistic Ranking-Aware Ensembles (PRAE).


## Models  

FCOS (ResNext101-FPN) with 42.5% mAP

Mask R-CNN (Res2Net101-FPN with 43.6% mAP

## Prerequisites 

* Python 3.6+

* mmcv >= 0.4.0

* numpy >= 1.16

* cocoapi


## Usage

python ensemble-2-models.py # implement PRAE  
python evaluate.py # calculate mAP on COCO2017 validation set


